# CSharpBridge
A Bridge that makes possible mod Minecraft in C#

# Discord
[the Discord Server](https://discord.gg/66jFwruquq)

# W.I.P.
This is a work in progress and at this moment there isn't any code yet, I'm still figuring out how to implemnt it the right way

# The idea
The idea is that a normal mod in Neo-Forge (C#Bridge) calls a .exe process (C#BridgeHost) that will handle the C# part. The two part will comunicate with a message system that will send json, that will be received and hadled by both parts. Each C# mod will have it's own enviroment and should expose an API and some hooks for other mod to integrate it. This should allow the use of multithreding for some calculation that don't need other mod. An examle could be that the Host receives a message that says that a block was broken and calls a C# event that notifies all the C# mods that handle the event in their own enviroment or even in their own thred then sent to the host the messege that should be returned to Neo-Forge

## Roadmap
1) Structure the architeture
2) Implement the bridge (C#Bridge) and the host (C#BridgeHost)
3) Implement an API similar to the Minecraft and Neo-Forge API in C#
4) Implement a way to use existing C# mod as dependecies (maybe net packet?)
5) Implement a way to use existing java mod as dependencies
6) Implement a way to expose something to the other java mod
7) Implement the multithreaded system

# If you want to help you are welcome to
I've a lot of expirience in c# and a bit in minecraft modding. Unfortunatly I'm pretty new to Neo-Forge. I'm slowly learning it, but if someone that already know it, or that want to learn it with me, is welcome to join the project.
And all help is welcome.

# Disclaimer 
I know that this is not something much useful and that it's a lot of work, but I think this will be a very interesting project. That maybe will grow and be useful to someone.

# Conclusion
I hope that this project will be helpful or interesting to someone else.

### P.S.
Sorry if my english is not so good but I'm italian
