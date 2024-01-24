To create a cronjobe for this script to run every month on the ansible master server you follow the steps bellow

# /bin/crontab -l
# /bin/crontab -e
# 0 0 1 * *  /usr/bin/ansible-playbook /home/vagrant/patch-servers/patch.yml
# 
