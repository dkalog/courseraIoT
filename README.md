##Deploy Bluemix
cd <directory>
###connect to bluemix
cf api https://api.eu-gb.bluemix.net

###Log in to Bluemix.
$ cf login -u juan.jordaan1234@gmail.com
$ cf target -o juan.jordaan1234@gmail.com -s dev

###Deploy your app
cf push courseraRaspberryPi

###access app
courseraRaspberryPi.mybluemix.net

