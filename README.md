# aws-lambra-native-modules
Script to launch a new AWS EC2 instance, install all needed software and build node_modules folder in order to use it in "AWS Lambda scripts"


sudo yum update
wget https://rpm.nodesource.com/setup_4.x
sudo sh setup_4.x
sudo yum install -y nodejs-4.3.2
mkdir lambda
cd lambda
wget URL_TO_YOUR/package.json (you can use a gist)
npm install
