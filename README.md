## ![logo](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png) docor ![npm](https://badge.fury.io/js/docor.png)

a smart and tiny doc-maker using default package.json by [turing](https://npmjs.org/~turing) 

### Installation
````
$ npm install docor
// or install globally
$ sudo npm install docor -g
````

### Use CLI

````
// ensure excutes in dirs have package.json,
// it will create README.md ,license .gitignore & .npmignore
$ docor
// 生成中文readme
$ docor -c README.zh-CN.md // 需要指定文件名，如果不指定文件名，会覆盖README.md
````

### Example
````javascript
var docor = require('docor');
````

### API

- docor.ignore()
- docor.readme()
- docor.license()
- docor.cli()

### Contributing
- Fork this repo
- Clone your repo
- Install dependencies
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Open a pull request, and enjoy <3

### MIT license
Copyright (c) 2013 turing


---
![docor](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png)
generated using [docor](https://github.com/turingou/docor.git) @ 0.0.4. brought to you by [turing](https://npmjs.org/~turing)
