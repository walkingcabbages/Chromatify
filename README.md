# Spotify Accounts Authentication Examples

Chromatify rediscovers your music memories. View your most listened-to tracks of all time on Spotify through our carefully designed web app.

Developed by Carnegie Mellon University CS students: Megan Xu, Amy Chang, and Sara Patel. Created on Oct 1-2, 2022 for HackMIT. 

Tools used:
* Node.js
* JavaScript
* HTML/CSS
* Spotify API

To run:
* Download node.js
* cd into repository
* Run 'npm start' in terminal
* Visit 'http://localhost:8888/' on your browser. 
* Authenticate with Spotify

## Spotify API Installation

These examples run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. You can also follow [this gist](https://gist.github.com/isaacs/579814) for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

    $ npm install

### Using your own credentials for Spotify API
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application. For the examples, we registered these Redirect URIs:

* http://localhost:8888 (needed for the implicit grant flow)
* http://localhost:8888/callback

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in the examples with the ones you get from My Applications.

## Running the examples
In order to run the different examples, open the folder with the name of the flow you want to try out, and run its `app.js` file. For instance, to run the Authorization Code example do:

    $ cd authorization_code
    $ node app.js

Then, open `http://localhost:8888` in a browser.
