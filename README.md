# ansible-infra

python3 -m pip install --user ansible-core==2.13.3

sudo pip3 install boto3

ansible-galaxy collection install -r requirements.yml -p ./collections/

ansible-inventory -i inventory/aws_ec2.yaml --list




