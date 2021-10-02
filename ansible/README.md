aws s3 cp s3://lasthm-ec2/ . --recursive --include "*.pem"
chmod 400 bluegreen.pem