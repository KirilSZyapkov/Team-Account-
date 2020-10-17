# Team-Account
As a gamer, Peter has Tseam Account. He loves to buy new games. You are given Peter's account with all of his games-> strings, separated by space. Until you receive "Play!" you will be receiving commands which Peter does with his account.` 

You may receive the following commands: 

Install {game} 

Uninstall {game} 

Update {game} 

Expansion {game}-{expansion} 

If you receive Install command, you should add the game at last position in the account, but only if it isn't installed already. 

If you receive Uninstall command, delete the game if it exists. 

If you receive Update command, you should update the game if it exists and place it on last position. 

If you receive Expansion command, you should check if the game exists and insert after it the expansion in the following format: "{game}:{expansion}"; 

Input 

On the first input line you will receive Peter`s account - sequence of game names, separated by space. 

Until you receive "Play!" you will be receiving commands.  

Output 

As output you must print Peter`s Tseam account.  

Constraints 

The command will always be valid. 

The game and expansion will be strings and will contain any character, except '-'. 
