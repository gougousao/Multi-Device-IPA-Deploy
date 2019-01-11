# Multi-Device IPA Deploy

1: git clone the repo and then cd to new folder.

2: run `sudo npm install -g ipa-deploy`

3: run `sudo npm install -g ios-deploy --unsafe-perm=true` (unsafe perm has to be used on El Capitan or higher)

4: run `brew install libimobiledevice`

5. run `brew install bash` (to update if need be)

6: run `chmod +x deploy.sh`

7: Add your resigned ipa to the DeployIPA folder.
(you can rename your ipa to `resigned.ipa` or change the filename in deploy.sh)

8: Run `./deploy.sh` in Terminal
