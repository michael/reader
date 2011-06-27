KollWi
================


Install
----------------
  
**Clone the repository**  

    $ git clone git@github.com:geraldstangl/kollwi.git

**Init submodules**

    $ git submodule init

Development
----------------

**1. Launch the browser**

    $ open index.html
    
**2. Edit files (javascripts, stylesheets, etc.) as usual**


Architecture
----------------

We are dealing with a service oriented architecture here. There are two parts involved:


**Backend**

Content is managed through an instance of Substance located at http://kollwi.substance.io.


**Frontend**

The frontend is an independent website that pulls data from the KollWi service (http://kollwi.substance.io) and displays it.


Deploy
----------------

Deployment is as simple as copying the contents to a webserver. It's just HTML+JS+CSS, you don't need any special server infrastructure.

For testing we use Github pages to host the application. http://geraldstangl.github.com/kollwi

However it could be deployed to Heroku for instance: http://kollwi.heroku.com