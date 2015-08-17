Installation:
Install aws-cli and python.

run the following command to set the key,secret and bucket of AWS account.
aws configure
aws_access_key_id = YOUR_ACCESS_KEY
aws_secret_access_key = YOUR_SECRET_KEY
You may also want to set a default region. This can be done in the configuration file. By default, its location is at ~/.aws/config:

[default]
region=us-east-1



Get PIP from here, download get-pip.py
https://pip.pypa.io/en/latest/installing.html

python get-pip.py

install boto3 with this command
pip install boto3




Create a directory at C: named screepy


copy screencheck.py file there.



Open Windows registry editor by pressing (Windows Key+R) and write "regedit".
Go to:

HKEY_LOCAL_MACHINE>SOFTWARE>Microsoft>Windows>CurrentVersion>Run>
Create a new entry named "screepy"
Select the entry, click on modify
Give the value as "C:\screepy\screencheck.py"


Reboot computer