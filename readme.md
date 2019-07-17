# playerManager

###Install
1. Stop Master Server
2. Navigate to the SharedPlugins folder
3. Run the command "node client.js manage shared plugins add https://github.com/Danielv123/playerManager.git" without quotations.
3.1 Alternatively you can run "git clone https://github.com/Danielv123/playerManager.git"
3.2 Or download the repo and place it directly in the SharedPlugins folder.  SharedPlugins/playerManager

### Create admin account
1. To make the first admin account with playerManager, open database/users.json
2. With a text editor, locate your user (under users, not managedPlayers)
3. Just below the line with "name", place this:  "admin": true,
