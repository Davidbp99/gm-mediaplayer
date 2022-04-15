Media Player
============

![Preview](http://images.akamai.steamusercontent.com/ugc/403430334757512796/4EFCE2D358BCAF42389E36B62CB11E9849842E07/)

Media Player is an addon for Garry's Mod which features several media streaming services able to be played synchronously in multiplayer.

### Installation ###

Place the contents of this GitHub repository into a new addon folder within your `garrysmod/addons/` directory. For those unfamiliar with Git, press the `Download ZIP` button in the right-hand sidebar.

If you'd only like to use the addon and not modify the source code, you can subscribe to the item on Steam Workshop:

[![Steam Workshop](http://www.pixeltailgames.com/elevator/images/workshop_button.png)](http://steamcommunity.com/sharedfiles/filedetails/?id=546392647)

### Config ###
In file gm-mediaplayer\lua\mp_menu\common.lua and gm-mediaplayer\lua\mp_menu\queue.lua

You can find the below to edit.



```glua
-- common.lua

local ranks = {
	"superadmin",
	"bronze_vip",
}

local steamidaccess = {
  	"STEAM_0:1:56187412" -- David

}

-- queue.lua
local staffrank = {
 "superadmin",
 "head_manager",
 "manager",
 "senior_admin",
 "admin",

}
```
