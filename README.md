## Project description

This is the source code for the "Polymer 2.0" presentation given by me at the CERN Spring Campus 2018 
at the RTU Univeristy in Latvia, Riga.

## Installation

First, make sure you have the [Node.js](https://nodejs.org/en/) installed. Then 
install the latest versions of the [NPM manager](https://www.npmjs.com/), [Bower](https://bower.io/)
and [Polymer CLI](https://www.npmjs.com/package/polymer-cli) by running the following commands:


```bash
npm install npm@latest -g

npm install -g bower

npm install -g polymer-cli
```

Now get necessary project dependencies using Bower. Bower will read the file 
**bower.json**, analyze which dependencies are needed, download and install them in the
**bower_dependencies** are needed:

```bash
bower install
``` 

If your PC says the command is not found you have to add your npm folder into the PATH. 
On a PC the default npm folder is in the {user_folder}\AppData\Roaming\npm but you can 
change it by editing the "c:\Program Files\nodejs\node_modules\npm\npmrc" file.

**Note.** Bower is deprecated even by its developers and you shouldn't use it for new projects
(use webpack or yarn or npm istelf). Polymer 3 will switch to npm but as Polymer 2.0 still actively
uses bower I've decided to use it too for this presentation.

## Running Demos

Use [Polymer CLI](https://www.npmjs.com/package/polymer-cli) to run examples. Polymer CLI can run a local 
web server so that you don't need to deploy those examples anywhere. Switch to your project directory and run
the local web server by doing the following command:

```
cd c:\dev\polymer-presentation
polymer serve
```

* Shadow DOM demo: [http://127.0.0.1:8081/shadowDOMDemo.html](http://127.0.0.1:8081/shadowDOMDemo.html) 
* Challenge 1 (The Google Map demo): [http://127.0.0.1:8081/googleMapDemo.html](http://127.0.0.1:8081/googleMapDemo.html)
* Challenge 2 (Input with a greeting): [http://127.0.0.1:8081/fancyInputAndGreetingDemo.html](http://127.0.0.1:8081/fancyInputAndGreetingDemo.html)
* Challenge 3 (Find country by its capital): [http://127.0.0.1:8081/countryFinderDemo.html](http://127.0.0.1:8081/countryFinderDemo.html)




