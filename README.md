faye-sample-app
===============

Faye is a set of tools for dirt-simple publish-subscribe messaging between web clients. It ships with easy-to-use message routing servers for Node.js and Rack applications, and clients that can be used on the server and in the browser.

This sample application is a simple public chat application that demonstrates the users subscribed for channels and publishing messages.

Server Setup:
=============

Start the faye server with this command 

$ rackup faye.ru -s thin -E production

Then start our rails application server

$ rails s

Browse the chat application in http://localhost:3000

