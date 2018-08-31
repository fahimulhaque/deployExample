# DeployExample

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Use of custom environment in Angular
* Add custom env file under environment folder.
* Update angualr.json file under project configuration section.

    ``"test": {
              "fileReplacements": [
                {
                  "replace": "src/environments/environment.ts",
                  "with": "src/environments/environment.test.ts"
                }
              ]
            }``

* Add configuration under serve build section.


    
        "configurations": {
                "production": {
                "browserTarget": "deployExample:build:production"
                },
                "test": {
                "browserTarget": "deployExample:build:test"
                }
* Thats it !!!