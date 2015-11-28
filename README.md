# Weather-app-with-Node-webkit-and-Angularjs
Weather app with Node webkit and Angularjs

##Tutorials
1. Part 1
2. Part 2

##How to run?
####Clone app
`git clone https://github.com/Inaamhusain/Weather-app-with-Node-webkit-and-Angularjs.git`

####Install npm packages
Install node webkit  
`npm install -g nw`  

Install node webkit builder   
`npm install -g nw-builder`  

To check it's working, Go to location inside the folder in command prompt, and type  
`nw`  

##Packaging the app
go to parent directory that contains the weatherApp folder. and type following command,  
`nwbuild -p win32,win64,osx32,osx64,linux32,linux64 appfolder`
