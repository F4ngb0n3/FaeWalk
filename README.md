# FaeWalk  
_Random Teleportation Plugin_

The official Documentation for the FaeWalk Minecraft Plugin  

**FaeWalk** brings you Random Teleportation to _ALL_ of your server worlds, even the Hub / Spawn worlds! With absolutely NO PERMISSIONS, **FaeWalk** gives your players the ability to pop around your worlds with ease & safety!  

> NOTE:  
> **If you used my previous RTP plugin, _Janky_, this is the most recent version! It went through MAJOR updates and overhauls and popped out the other end as FaeWalk**  

### Configuration
Setting up the config is easy; you don't have to! Just kidding...

| Value | Default | Description |
| --- | --- | --- |
| `open-faewalk` | false | Enables / Disables the ability for players to teleport OUTSIDE the default Minecraft worlds; i.e., Hub / Spawn / Resource Worlds |
| `faewalk-wait` | true | Enables / Disables the FaeWalk countdown timer. Basically, do your players have to wait to RTP |
| `faewalk-timer` | 100 | Number of ticks the players will wait if `faewalk-wait` is set to TRUE. Defaults to 5 seconds = 100 ticks |
| `faewalk-limit` | 2000 | The radius in blocks the player is allowed to teleport within from their current location |

####  

### Command List
Minimal commands on this one, broh. Look at them below, broh.  

> NOTE:  
> _There are no permissions for **FaeWalk**, however 2 of the commands require an OP to use_  

| Command | Args | Aliases | Description | OP |
| --- | --- | --- | --- | --- |
| `/faewalk` | [WorldName] _(optional)_ | `/fw` | Allows players to teleport randomly in the world they are in. If [WorldName] is supplied, then they will be randomly teleported to a location in the given world | No |
| `/faewalkdisable` | N/A | N/A | Add the world **YOU ARE STANDING IN** to the `Disabled Regions` list so teleporting does NOT work in that/to that world | Yes |
| `/faewalkenable` | N/A | N/A | Remove the world **YOU ARE STANDING IN** from the `Disabled Regions` list so teleporting DOES work in that/to that world | Yes |

####  
## Support
**F4ngdev** is always working tirelessly to ensure quality functional plugins, and should any questions or needs arise, we invite you to open a support ticket here on the **CakeSMP Github** where we can manage and get all things plugin related handled. If this forum isn't working for you, we always have the [**F4ngdev Discord**](https://discord.gg/k28sR69n5f) where everything plugin and development related is open-discussion.

