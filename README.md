# devops-test-solution
In this assessment, I have designed a NodeJS appliation with Express, Lynx and Request modules with a logic to connect to remote servers/urls and perform NO action.

I have also created a Docker Image and started this NodeJS Application as a container named "nodejs-statsd"  and started another container named graphite from the official Graphite-StatsD image

I created a Docker Network and Connected these containers together and enabled connectivity between each other.

Now you can access the URLs we have designed in the index.js file on our Application /GaugesApp, /TimerApp etc.

It has been hosted on AWS so you can try these URLs:

http://3.14.54.249:8080/GaugesApp

http://3.14.54.249:8080/

http://3.14.54.249:8080/TimerApp

