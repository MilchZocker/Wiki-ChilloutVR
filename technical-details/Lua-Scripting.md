---
title: LUA Scripting
description: Advanced comprehensive technical information for ChilloutVR Scripting.
published: true
date: 2024-06-01T18:42:46.718Z
tags: cck, community, content creation, lua, scripting
editor: markdown
dateCreated: 2024-06-01T18:42:46.718Z
---

# LUA Scripting

> This page is still being worked on!
> Contact Shinter to add or suggest stuff for the page.
> Alternatively, you can also contact MilchZocker to edit the page.
{.is-warning}




# LUA Creation


> This is the example provided by the official documentation.
{.is-info}


1. Create a new folder in your project called Lua. This isn't required, but may help you organize things.
1. Create a new folder in Lua called Hello World. Again, not entirely necessary.
1. Right-click the folder and select Create > CVR Lua Script.
1. Name it helloworld.lua
1. Open your project folder (the folder above Assets) with VSCode.
1. In your VSCode project window, locate and open helloworld.lua.

```
-- Start is called before the first frame update
function Start()

end

-- Update is called once per frame
function Update()

end
```


# Lua Function Examples
You can add any of the snippets below to your lua code and use them as a function.

## Debug Print
```
DEBUG_MODE = false
local function DebugPrint(message)
    if DEBUG_MODE then
        print(message)
    end
end
```
### Usage of function

When set to true on script load it prints the message: Hello! Script Loaded!
```
DEBUG_MODE = true
local function DebugPrint(message)
    if DEBUG_MODE then
        print(message)
    end
end


function Start()
DebugPrint("Hello! Script loaded!")
end
```





# API Reference

[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/)
## Globals
[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/globals/)
## Callbacks
[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/callbacks/)
## InstancesAPI
[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/instances-api/)
## PlayerAPI
[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/player-api/)
## AvatarAPI
[Official Documentation](https://documentation.abinteractive.net/cck/lua/api/avatar-api/)

## Resources

Check out these resources to learn more:

- [Learning Lua - A beginner's guide to scripting](https://steamcommunity.com/sharedfiles/filedetails/?id=714904631)
- [Learning MORE Lua - An intermediate guide to scripting](https://steamcommunity.com/sharedfiles/filedetails/?id=879449506)
- [ChilloutVR Official Website](https://abinteractive.net)
- [ChilloutVR Discord Community](https://discord.gg/ABI)
- [ChilloutVR Wiki Documentation](https://wiki.chilloutvr.eu)

Feel free to explore the ChilloutVR Wiki and contribute to its growth. Together, let's build a comprehensive resource for the ChilloutVR community!

If you have any questions or need further assistance, please don't hesitate to reach out. Enjoy your time in ChilloutVR!

*Note: Not affiliated with Alpha Blend Interactive, this is entirely Community provided and maintained.*
