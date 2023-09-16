## __MODULE - II__
---

### 1. Install npm and node
```
Check npm -v
Check node -v
```

#### 2. __Create a new project__
    ---
    * npm init
        * package.json
    * npm install jquery
        * package.json
        * package-lock.json
        * node_modules
### 3. __Architecture__
![](../summary/images/2023-07-23-06-55-59.png)

### 4. Installing Angular cli
```
npm install -g @angular/cli@7.0.3
```
### 5. Check the CLI version
```
ng version
```

### __ERROR__ Resolving error ng disabled
----

[Reference](https://www.c-sharpcorner.com/article/how-to-fix-ps1-can-not-be-loaded-because-running-scripts-is-disabled-on-this-sys/)

### 6.  Creating new Angular Project Using CLI
----
```
ng new todo 
ng serve 
```

## __MODULE III__
---
### 7. CLI commands
* ng lint [Refer Here](https://angular.io/cli/lint)
```
Linting is the process of checking the code quality and style, and finding and fixing errors or potential problems.
 ```
* ng build [Refer Here](https://angular.io/cli/build)
```
* It is used to build and compile our Angular application into a distributable format that can be deployed to a web server or hosting platform.
* Generate output files in a dist directory by default (configurable).
```
* ng test [Refer Here](https://angular.io/cli/test)
```
* Used to run unit tests for our Angular application.
* It provides a convenient way to execute unit tests written using testing frameworks like Jasmine and test runners like Karma.
* The tests are typically located in files with a .spec.ts extension (e.g., app.component.spec.ts).
```
* ng ete [refer Here](https://angular.io/cli/e2e)
```
* Builds and serves an Angular application, then runs end-to-end tests using Protractor.
* code coverage 
```

![](../summary/images/2023-07-23-14-45-53.png)

 ### __ERROR__ Resolving build issue - Error message "error:0308010C:digital envelope routines::unsupported"

[Reference](https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported)

```
choco install nodejs.install --version=16.0.0 --allow-downgrade
```



