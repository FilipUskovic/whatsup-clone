# WhatsupCloneFront


kreirao sam prvo stylove i konfigurirao import za fontAwesoke i druge slicne stvari
kreirao sam loyout kako ce izgledati whatsapp
dodao sam state model, user model authenticatiom i request model s pagination
insalirao dependecy za dayjs i ngxtension
dodao servis outhaservice i envirometn s podesenim keycloak-om

dodao silentCheckSsoRedirectUrl.html jer je potreban kod inicjalne inteditifiackje key-cloak-a
dovrsaio outh-atuh servide 


kreirao auth model componentu i dodao slike

kreiralo smi u outh2 modulu html s kreiranim div buttonom i d-flex flex column 

te trebati ce nam 2 interceptora :
 1 http-auth interceptor s 2 par req i next ( u toj metodi svaki put kada napravi http request injectat ce Bearer token unutar authorizatin header-a)
 2 u slucaju da je excess token istekao
te ih moramo doati unutar naseg appConfiga

te smo dodali u component app init authenitcation i outh service injectali

ddaod u anglr js path za srv assets da se slika moze vidjeti

kreirao navbar komponentu
i uredio scss stil de

kreirali smo nav bar s ngbDropdown menuom te dodali i app component html idnex



This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
