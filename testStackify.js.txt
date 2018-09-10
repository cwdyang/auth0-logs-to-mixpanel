var stackify = require('stackify-logger');
 
// this should be executed only once in the app
stackify.start({apiKey: '2Wf4Ak3Kp2Tl8Ss7Ad1Ra7Hh8Px3Bl5Wq8Pt8Oq', env: 'testing'});

stackify.error("AUTH0");

stackify.log("info","AUTH0");
