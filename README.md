# holygrail


## Steps 
https://medium.com/codingthesmartway-com-blog/building-an-angular-5-project-with-bootstrap-4-and-firebase-4504ff7717c1

https://scotch.io/tutorials/deploying-an-angular-cli-app-to-production-with-firebase#firebase-hosting-dashboard

### Install angular
npm install -g @angular/cli

### Install firebase and angularfire2
npm install firebase angularfire2 --save

### Install bootstrap
npm install --save bootstrap

### Install ng-bootstrap
npm install --save @ng-bootstrap/ng-bootstrap

### Firebase init
firebase init

### Build for production
ng build --prod

### Firebase deploy
firebase deploy

or

npm run deploy

### Open
firebase open hosting:site

### Deployment 
https://theholygrailapp.firebaseapp.com/

## Tips 

To remove environment.ts from git : 
git rm --cached holygrail/src/environments/environment.ts
