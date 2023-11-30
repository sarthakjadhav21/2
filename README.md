# 2
Title-
Use GAE launcher to launch the web applications

Steps-
a. Already you have installed google cloud SDK and python

b. Write the configuration file
c. Write the web application file
d. Deploy and run it

Video Link-
https://www.youtube.com/watch?v=KrN7yg2Kqxo

app.yml file consist of all the configurations related your particular file or folder.
main.py file consit of logic of the projcet.
templets/ folder consist of all the templets which we are going to render in the main.py file is there.
static folder cosist of all the static files like html, css.

in app.yml: we have mentioned 4 things: Runtime, API version of that partiular SDK, Threadsafe (for single thread and not multiple threads to run), Handlers.

in google cloud sdk shell: run "py google-cloud-sdk\bin\dev_appserver.py folderlocation" and then press enter. Then copy the link which will look like this: "http://localhost:8080" and then paste in browser. If you want to change in the text, then change text in test.py file then ctrl+s then ctrl+r in browser.
