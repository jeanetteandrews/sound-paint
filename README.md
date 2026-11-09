## What's in this project?

← `public/client.js`: The JavaScript for the site's front-end. This connects to a socket to talk to the server and uses p5.js and socket.io to send data about user interactions.

← `public/index.html`: This is the main index for the site. 

← `public/sharedView.html`: Shows all connected clients (except for itself) in a visualization.

← `public/sharedView.js`: Provides the JavaScript (p5.js and socket.io) necessary to render the visualizations in host.js

← `server.js`: The **Node.js** server script for your new site. In this example, we set up some socket.io communication between client & host in addition to serving HTML, CSS, and JS files.

← `package.json`: The NPM packages for your project's dependencies.