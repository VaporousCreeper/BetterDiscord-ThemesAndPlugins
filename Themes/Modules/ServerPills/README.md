# ServerPills
A mini-theme to shrink servers/guilds to size of your liking. It also supports a plugin called ServerFolders by DevilBro

## How to use
Add `@import url("https://vaporouscreeper.github.io/BetterDiscord-ThemesAndPlugins/Themes/Modules/ServerPills/ServerPills.css")` into one of your theme files or into your customcss in BetterDiscord settings.<br/> 
Then change the following settings that you want

### Settings
| Setting Option | Definition | Default |
| ----- | ----- | ----- |
| SP_Closed | Sets the height of the server/guild when it's not opened nor hovered | 25px |
| SP_Opened | Sets the height of the server/guild when it's opened or hovered | 50px |
| SP_BorderRadius | Sets the border-radius of the server/guild | 15px |
| SP_Duration | Sets the transition-duration of the server/guild when it's opened or closed | 200ms |
| SP_AnimationType | Sets the transition-timing-function of the server/guild when it's opened or closed <br/> More about transitions here: https://www.w3schools.com/css/css3_transitions.asp | ease-in-out |

### Examples
#### Default vars
```
:root {
   --SP_Closed: 25px;
   --SP_Opened: 50px;
   --SP_BorderRadius: 15px; 

   --SP_Duration: 200ms;
   --SP_AnimationType: ease-in-out;
}
```
#### Example One
```
:root {
   --SP_Closed: 15px;
   --SP_Opened: 50px;
   --SP_BorderRadius: 0px; 

   --SP_Duration: 100ms;
   --SP_AnimationType: ease-in;
}
```

## Notes
This module is free for everyone to use in any theme but if you're using the module for a theme to go public, make sure you add me to the credits<br/>
Don't hesitate to ask questions about this module

## Preview
![Preview1](https://raw.githubusercontent.com/VaporousCreeper/BetterDiscord/master/Themes/Modules/ServerPills/ServerPills_Preview.png)
