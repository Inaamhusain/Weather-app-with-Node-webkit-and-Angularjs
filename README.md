# Weather-app-with-Node-webkit-and-Angularjs
Creating Weather desktop app with **Node webkit** and **Angularjs**. which shows informations like place name, Temprature, weather info (i.e: cloudy, rainy etc.) and GEO location co-ordination.

##Tutorials
1.[Weather app with Node webkit and Angularjs : part 1](http://code.ciphertrick.com/2015/12/01/weather-app-with-node-webkit-and-angularjs-part-1/ "Weather app with Node webkit and Angularjs : part 1")  
2.[Weather app with Node webkit and Angularjs : part 2](http://code.ciphertrick.com/2015/12/01/weather-app-with-node-webkit-and-angularjs-part-2/ "Weather app with Node webkit and Angularjs : part 2")

##How to run?
####Clone app
`git clone https://github.com/Inaamhusain/Weather-app-with-Node-webkit-and-Angularjs.git`

####Install npm packages
Install node webkit globally  
`npm install -g nw`  

Install node webkit builder globally   
`npm install -g nw-builder`  

To check whether it's working, Go to location inside the folder in command prompt, and type following command  
`nw`  

##Packaging the app
go to parent directory that contains the weatherApp folder. and type following command,  
`nwbuild -p win32,win64,osx32,osx64,linux32,linux64 appfolder`  

**Note** : While packaging app if you will get any error like file missing or any other errors. download nw.js from it's official website([http://nwjs.io](http://nwjs.io "http://nwjs.io")) and place whole folder to its particular location which you can see the path in error. or else there is another way you can try this ( [https://github.com/nwjs/nw.js/wiki/How-to-package-and-distribute-your-apps](https://github.com/nwjs/nw.js/wiki/How-to-package-and-distribute-your-apps "https://github.com/nwjs/nw.js/wiki/How-to-package-and-distribute-your-apps") ) documents for packaging app.
