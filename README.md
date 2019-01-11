# Multi-Device IPA Deploy

1: git clone the repo and then cd to new folder.

2: run `sudo npm install -g ipa-deploy`

3: run `sudo npm install -g ios-deploy --unsafe-perm=true` (unsafe perm has to be used on El Capitan or higher)

4: run `brew install libimobiledevice`

5: chmod +x deploy.sh

6: Add your resigned ipa to the DeployIPA folder.
(you can rename your ipa to `resigned.ipa` or change the filename in deploy.sh)

7: Run `./deploy.sh` in Terminal
