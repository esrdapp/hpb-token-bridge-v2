# hpb-token-bridge-v2
based on POA token bridge

Ensure you have node, yarn and git installed. Install "git for windows" if you are running a windows PC as this will include Git Bash which allows you to run shell scripts.

Creae a suitable folder (e.g. tokenbridge)

navigate to the folder, then clone the repo with the following command:

git clone --recursive https://github.com/poanetwork/tokenbridge

navigate into the nely created tokenbridge folder and run the following command:

yarn install && yarn install:deploy

once you've done that, switch to the contracts folder and run:

npm run compile

Once complete, run:

deploy.sh

(IF using Windows, Git Bash will launch this in a bash window)

If you can't get it to work in linux try,

sed -i -e 's/\r$//' deploy.sh
deploy.sh










