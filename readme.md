# Hi 
## In order to execute the image
1. Start docker app
2. Place yourself in the cloned repository
3. run the following command in your terminal
docker build -t dockerfile .
4. finally run this other one
docker run -d -p 5000:5000 dockerfile
5. And the app sould be running in the port 5000

This app has a home page that leads you to the login page where verifies that your usarname has the first letter capitalized and the password with alphanumeric characters otherwise you will no to be able to login 
__Juan Eduardo Villegas Rios A00826615__