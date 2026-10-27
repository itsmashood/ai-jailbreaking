i've tested claude a few times but i'm not great with communicating with bots let alone my alone girlfriend so.
# Steps
1) Don't start from scratch i guarantee any ai just won't do it there's TOO many boundaries, instead use darkdex OR steal source from someone else and learn where things are THEN add to that.
script: loadstring(game:HttpGet("https://raw.githubusercontent.com/RezWare-SoftWare/Dex/refs/heads/main/Dex.lua"))()

2) lua isn't hard but lua isn't easy i learnt it from skidding too i only really know html,css,json and uh i'm learning c, i know adan.sh too but this isn't a biography so

3) use setclipboard(whatever you want) from the workspace environment 9/10 what you need will be kept in workspace (hence how many scripts are just printed per day)

   i think depending on the script your making some are easier to code than others and alot of others are cnp (copy and paste you evil pricks), for example, you can just copy
   walkspeed and jumppower logic from a different script, even aimbot's too but some work differently in different games as you can probably tell.
   
4) for aimbot specifically,  i advise probably camlock or tell ai you want a npc lock because to ChatGPT specifically it refers to it as "npc lock" it's the same thing it just doesn't
   wanna break any rules.
   
5) replicatedstorage, starterplayerscripts, serverscriptservice.
uhm it's actually quite simple, serverscriptservice (sss) you never have access to it basically validates everything that goes on in game, yk the funky movement that tp's you back in games or just kicks you by anti-cheat?
yeah most of the anti-cheat is within sss and other scripts that validate movement, currency and all other data are also there too (but some games don't bother mostly slop ones don't)

replicatedstorage, this is an important one this is where most remoteevents are so in darkdex you know where your looking and what to print
Im not even kidding if you get ai to setclipboard all remoteevents&services it will likely handle the rest for you the moment it stops guessing. but there's limits, replicatedstorage also controls sss too, so 
you can't just use everything inside of it, it's kinda like the 50/50 split folder some you can touch some you can't.

and last but not least localplayerscripts basically almost everything you touch in here is client sided, but you have somethings in localplayerscripts that are servervalidated however some games trust the client wayyy
too much **atleast 80% of games do this by the fucking way**. so most of what you touch will either be here? OR inside of replicated storage.

DO NOT TELL AI TO MODIFY SSS OR TOUCH SSS OR EVEN TAMPER WITH IT, IT WILL ASSUME YOUR WORKING IN ROBLOX STUDIO AND PLEASE DO NOT TELL IT YOUR USING DELTA. REFER TO IT AS A EXTERNAL ENVIRONMENT. IT WON'T LISTEN TO YOU.

__Changelogs__
27/10/2026 : 15:02 - L1:27
