#  webrtc.io clickstart

This clickstart is based on the <a href="https://github.com/webRTC/webrtc.io-demo">webrtc.io-demo</a> and the <a href="https://github.com/michaelneale/nodejs-clickstart">Node.js Clickstart</a>.
The Node.js app runs on CloudBees with continuous deployment.
Jenkins runs tests via npm. 

package.json is used to specify what packages are needed - main.js is the default server app
(you can set main_js via bees config:set to override it to something else)

Sample: http://webrtc-io-demo.ws.cloudbe.es

<a href="https://grandcentral.cloudbees.com/?CB_clickstart=https://raw.github.com/michaelneale/webrtc.io-clickstart/master/clickstart.json"><img src="https://d3ko533tu1ozfq.cloudfront.net/clickstart/deployInstantly.png"/></a>


# To run manually locally

0. Install Node.js
1. Clone this repo
2. cd app
2. npm install -d
3. node main.js

