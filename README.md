# TrelloSmoke

1. To run tests from this collection first obtain your API key and Token (to your Trello user) ((https://trello.com/app-key))
2. In the env file add your values for token and key as well as provide "Board Name", "List Name", "Card Name" of your choice 
3. You can runn test scripts in Postman runner or using Newman 
4. To install Newman install latest version on Node.js
5. On your terminal runn $ npm install -g newman 
6. Once installation is complete run your collection (be careful to run the collection from the correct folder) 
7. Include your env file (that you have previously exported) $ newman run "CollectionName" -e "EnvName"

One env file contains board, list and card name, other one is empty allowing you to enter your values for the variables
