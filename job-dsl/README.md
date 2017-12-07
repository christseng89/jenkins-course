# exec docker

docker exec -it jenkins bash

cd /var/jenkins_home/workspace
cd "NodeJS example"

ls -l

find ~ -name "npm"

export PATH=$PATH:/var/jenkins_home/tools/jenkins.plugins.nodejs.tools.NodeJSInstallation/nodejs/bin

npm start
