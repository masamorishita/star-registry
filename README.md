# Prerequisite
In order to run the code, you need to install Node.js and npm in your computer.

# Run the application
After you clone the repositry, run the following command to launch the application.
```
$ node app.js
```
Now you should be able to access the application on the URL http://localhost:8000/


# How to use the application

## 1. Access to the specific block

You can access to a specified block by using GET call with the following URL:
```
http://localhost:8000/block/<HEIGHT OF THE BLOCK YOU'D LIKE TO ACCESS>
```
For example, if you access the genesis block (URL: http://localhost:8000/block/0) it looks like as followed.
https://user-images.githubusercontent.com/2709242/58421275-8551f200-80ca-11e9-93ff-13ef2c23f653.png
