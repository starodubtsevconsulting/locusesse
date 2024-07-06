```shell
npm --version
node --version
mkdir infrastructure
npm install
sudo npm install -g aws-cdk-local aws-cdk
cdk init app --language typescript

cd ..
git init
touch .gitignore
git add .

git remote set-url origin https://github.com/starodubtsevconsulting/locusesse.git
git commit -m "initial commit"
git push -u origin main
```


```shell
cd infrastructure
npm run build
cdk synth
```
