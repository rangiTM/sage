# Sage 8.5.3 with Bootstrap 4
If you are like me and can't use Sage 9 for whatever reason you may find this useful if you want to use Bootstrap 4 release version in a project. 

- Bootstrap 4 and popper.js are loaded using npm instead of bower 
- bootstrap.js is working and added to main.js
- I added JSHint exceptions for node_modules to gulpfile.js so production deploys work
- bower.json and bower_components are still included if you want to use some bower package

That's it. Enjoy!