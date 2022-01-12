### snapinator: localhost, no port
a frontend that will be served by express and puppeteer in remote. 
**to serve this, you have to open manager-osx for apache**
`cd /Applications/XAMPP/xamppfiles/htdocs/snapinator`
`git checkout snapinator-service`
`npm run build`

to see the page, go to:
http://localhost/snapinator/dist/

## snapinator-service: 9090
the service that serves snapinator
just go to webstorm and click run.


//## Redis server: 6379
//it uses a redis database to save temporary xml files. 


## snap-replay: 3000
the front-end for snap-replay
`cd /Applications/XAMPP/xamppfiles/htdocs/snap-replay/`
`npm run start`

## ScratchClip: 8080
Spring backend for snap-replay
`cd /Users/wwang33/Documents/IdeaBuilder/ProjectIdeaBuilder/ScratchClip`



todos
- 6.1.2 and 7.1
- 