TO REPRODUCE:

npm install -g @angular/cli
npm install -g ionic

mkdir p33t_proj\

cd p33t_proj\

ionic start p33t blank --cordova --project-id=p33t --package-id=co.p33t.www

cd p33t\

npm i --save @angular/material @angular/cdk @angular/animations hammerjs @angular/flex-layout @angular/fire firebase





Update Main.ts
    - import 'hammerjs';

Update angular.json
    - "schematics": {
        "@schematics/angular:component": {
          "style": "sass"
        }
      }





Serve Options:

    (Angular serve, defaults to port 4200)
    ng serve
    
    (Ionice serve, with Lab. Lab Shows iPhone and Android instances. Also Website Instance. Ports 8100,8200)
    ionic serve -l

    I like to open two terminals and serve both
