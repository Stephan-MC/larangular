# Larangular
If you have thrived looking for a repo that will work with both laravel and angular, you are at the right place.
After years of reasearch i managed to find a breakthrough configuration.

This is repo is quite simple and easy espacially for those from the laravel background.


## Requirements
- this repo **MUST** be launched using a virtual host.
- You **MUST** be familiar with laravel and angular.


## Installation
- clone this repo
``` git clone https://github.com/Stephan-MC/larangular/edit/main/README.md ```

- Add a virtual host matching the *public* directory of this project
- edit your package.json file as shown below to ensure angular local server will be running on your vhost. Please remember to change **{larangular.test}** to your configured vhost
```json
{
  ...
  
  "scripts": {
    "ng": "ng",
    "start": "ng serve --host {larangular.test} --port 80",
    "build": "ng build",
    "watch": "ng build --watch --configuration development",
    "test": "ng test"
  },
}
```
- run ``` composer install``` to install laravel composer packages
- run ``` npm install``` to install required node_modules
- Run ``` ng serve``` and enjoy 

# 
If any problem is encountered, please kindly drop an issue or contact me via the following media
- twitter [@Stephan__MC](https://twiiter.com/Stephan__MC)
- Email me for any enquiries [mundestephane13@gmail.com](maito:mundestephane13@gmail.com)
