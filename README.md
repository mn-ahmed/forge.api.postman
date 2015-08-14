# Autodesk View & Data API Postman Collection

[![LMV REST](https://img.shields.io/badge/View%20%26%20Data%20API-v1-green.svg)](http://developer-autodesk.github.io/)
![Platforms](https://img.shields.io/badge/platform-windows%20%7C%20osx%20%7C%20linux-lightgray.svg)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://opensource.org/licenses/MIT)


An AutodeskView & Data API postman collection, environment with JetPacks support.

Demonstrates the Autodesk View & Data API authorisation and translation process using a Postman Collection.


## Description

The view.and.data.api.postman collection exercises the Postman tool to demonstre the Autodesk View and Data API
authorisation and translation process mentioned in the Quick Start guide.

It closely follows the steps described in the documentation:
* http://developer.api.autodesk.com/documentation/v1/vs_quick_start.html

In order to make use of this sample, you need to register your consumer key, of course:
* https://developer.autodesk.com > My Apps

This provides the credentials to supply to the HTTP command arguments.


## Motivation

What do you think about setting up the Chrome Postman tool that does nothing but execute the REST call provided in 
the quick start documentation?

That would presumably help developers debugging their processes quickly.


## Postman and setup

### Installation

Postman is a Google Chrome App that allows you to quickly use and test API calls with our system, with features that 
help to streamline and optimized your calls, as well as inspecting server responses.

To download Postman, simply follow [this link](https://chrome.google.com/webstore/detail/postman-rest-client-packa/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)
and click on “Add to Chrome”.

To launch Postman, open your chrome apps by clicking on the button to the left of the browser.
![](images/launch-postman.png)

If the button isn’t there, you can use the ‘cmd-shift-B’ shortcut on OSX, and the ‘ctrl-shift-B’ shortcut on Windows.

Then, click on the Postman icon to launch the app.
![](images/postman-icon.png)

Postman will then open in a new window, ready to set up an environment.


### Environment

Setting up an environment allows us to easily use environmental variables, which will make calling to the API easier, and quicker.
To do so, we click the downward arrow next to ‘No environment and select ‘Manage environments'
![](images/manage-env.png)

At the next window that opens, click ‘Import’.
![](images/import-env.png)

and use this url to import the environment: https://raw.githubusercontent.com/Developer-Autodesk/view.and.data.api.postman/master/Autodesk%20View%20%26%20Data%20API%20Production%20Server.postman_environment

Next, click the 'Back' button, and then select the 'Autodesk View & Data API Production Server' link.
![](images/edit-env.png)

Finally, enter your Autodesk View & Data API keys, and click 'Submit'.
![](images/edit-key-env.png)


### Collection

Postman uses collections, which can be used to add groups of API calls in order to automate the process of using/testing a REST API.
This official Autodesk View & Data API Postman collection is to help get you to test and debug the API easily.

To set up Postman with the Autodesk View & Data API collection, make sure that you are on the collection tab on the left, and click ‘Import collection'
![](images/import-collection.png)

Choose 'Download from link', and copy the URL below, then hit the 'Import' button.
https://www.getpostman.com/collections/14e42c06b5f44aa2f88f


## Using Postman

Using Postman with the Autodesk View & Data API is the exact same as making many manual HTTP requests, only easier. 
Lets go through some example API calls so that you can get a feel for how it works with Postman.


--------

## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.


## Written by

Cyrille Fauvel (Autodesk Developer Network)<br />
http://www.autodesk.com/adn<br />
http://around-the-corner.typepad.com/<br />
