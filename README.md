# Weather-app-with-Node-webkit-and-Angularjs
Creating Weather desktop app with **Node webkit** and **Angularjs**. which shows informations like place name, Temprature, weather info (i.e: cloudy, rainy etc.) and GEO location co-ordination.

##Tutorials
1.[Weather app with Node webkit and Angularjs : part 1](# "Weather app with Node webkit and Angularjs : part 1")  
2.[Weather app with Node webkit and Angularjs : part 2](# "Weather app with Node webkit and Angularjs : part 2")

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
