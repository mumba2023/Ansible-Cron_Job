To create a cron job for this script to run every month on the ansible master server you follow the steps bellow

# /bin/crontab -l
# /bin/crontab -e
# 0 0 1 * *  /usr/bin/ansible-playbook /home/ec2-user/patch-servers/patch.yml
# 
