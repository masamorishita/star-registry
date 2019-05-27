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
![Screenshot 2019-05-27 at 21 47 50](https://user-images.githubusercontent.com/2709242/58421275-8551f200-80ca-11e9-93ff-13ef2c23f653.png)

## 2. Request validation
In order to request a validation for your wallet address, you can make POST call with the following URL

```
http://localhost:8000/requestValidation
```
You need to include the following JSON on the body:
```
{
	"address": <YOUR WALLET ADDRESS>
}
```
If you make the POST call successfully, it should look like as followed:
![Screenshot 2019-05-27 at 21 52 01](https://user-images.githubusercontent.com/2709242/58421276-85ea8880-80ca-11e9-81b8-627255e4dc28.png)
