# Instruction for the entire project
 for this project you need to clone two repositories, the first one is is this repositry (Chat-App-Server), and the second repository is under under this account
 under the name Chat-App-Client.
 
 ## Chat-App-Server instructions
 after cloning Chat-App-Server repository, do the following :
 1) open the solution on Visual Studio.
 2) set the Web-server as the strart-up project.
 3) in the Package Manager Console type - update-database init
 4) set the web-api as the start up project and run it

## Chat-App-Client instructions
after cloning Chat-App-Client repository, do the following :
1) open the terminal in the cloned folder
2) type npm install
3) type npm start

##

now you have the client side which shows the chat and the server siden which shows the api funcitionalty on the swagger interface running on your local browser.

pay attention to the following
the api-server is runing on port 7182 and can communicate with localhost:3000, and localhost:3001 only
