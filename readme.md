**A FiveM DevTool**

**Description**  
The `DevTool` is a Lua-based development tool for FiveM servers, providing essential debugging features and tools for developers. It offers easy-to-use commands that display various information about players, vehicles, NPCs, bones, and more in the game world. This script is designed to assist developers during the creation, testing, and debugging of FiveM server resources.

**Installation**  
To install `DevTool`, simply follow these steps:

1. Download the `DevTool.lua` script file.
2. Place the `DevTool.lua` file in your server's resources folder.
3. Add `ensure DevTool` to your server's `server.cfg` to ensure the script loads when the server starts.

**Commands**

1. **/devcoords**  
   Toggle the display of the player's current coordinates (X, Y, Z), heading (H), rotation (RX, RY, RZ), speed, health, camera rotation, and vehicle information (if inside a vehicle).

2. **/devplayers**  
   Toggle the display of player information such as name, session ID, health, armor, and coordinates for all players within the game world.

3. **/devpeds**  
   Toggle the display of NPCs' information, including the entity hash, name, and coordinates, for all NPCs near the player.

4. **/devvehicles**  
   Toggle the display of vehicle information such as model hash, name, coordinates, and rotation for all vehicles near the player.

5. **/devprops**  
   Toggle the display of prop information, including hash, name, coordinates, and rotation for all objects near the player.

6. **/devbones**  
   Toggle the display of specific bone coordinates for the player, displaying information for predefined bones (e.g., head, arms, legs, etc.).

7. **/devtrafficnodes**  
   Toggle the display of traffic node information, useful for debugging AI pathing and routing.

**Customization**  
You can extend or modify the functionality of `DevTool` by editing the script directly. For example, you can add custom information to be displayed, or add new commands and features specific to your server.

**License**  
This script is copyright protected by Quravat Studios. It cannot be redistributed, modified, or used for commercial purposes without explicit permission from Quravat Studios.
For inquiries or permission requests, please contact **contact.quravat@gmail.com**.

**Disclaimer**  
This script is intended for development purposes only. It may contain bugs or performance issues in certain environments. Use with caution on production servers.

**Contact**  
For any issues, questions, or feedback, please reach out to **contact.quravat@gmail.com**.
