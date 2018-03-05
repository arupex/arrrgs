# arrrgs
For those times you want args to just be a global map

# install
    npm i arrrgs --save 

# usage
    
    node app.js --remoteUrl=192.168.1.1:1337 --seleniumUrl=192.168.1.2:4444
    
    
in app.js

    require('arrrgs');
   
    browser = new Browser(ARGS.seleniumUrl);
    browser.goto(ARGS.remoteUrl);
    ...
    
    