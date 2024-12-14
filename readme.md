idea is to automate and speedrun the factorio using Automod or Ai agents or whatever it takes


useful things:
https://lua-api.factorio.com/latest/index-runtime.html
https://github.com/clusterio/clusterio
https://forums.factorio.com/viewtopic.php?f=120&t=23655

https://forums.factorio.com/viewtopic.php?t=39327

"
I think the whole determinism argument is a bit of a crappy reason in my opinion. Just simply telling the user not to use it to make something happen in the game (other than loading blueprints or whatever) is enough.

Its like saying disallow mods because a user can accidentally write incorrect code (ie not using the right syntax), of course they can but as long as they know not to then it shouldnt be an issue.

Things like two way sockets or reading a file can enable some very cool things such as live online maps or telementary for the game (eg Kerbal Space Programs telamechus mod).
"

"
1) People don't know how to write incorrect code. People don't follow instructions like "Don't use this method, it will break determinism and it will desync". This has been proven time and time again.
2) When something like this happens, and someone downloads such broken mod and it breaks the game, where do they report it? To the mod author? No. To us, we have to go in, figure out whether the problem lies with our code or someone elses and send them their way. That takes a lot of our time and it's just wasteful. But it does have a simple solution - not including things like game.read_file.
Top
"


https://memorycorruption.net/posts/rce-lua-factorio/

https://forums.factorio.com/viewtopic.php?t=102241


we got storage boys:
https://lua-api.factorio.com/latest/auxiliary/storage.html

https://github.com/factoriommo/factoriommo-agent


if guy can do rce than we can definitely can automate this thing, but sadly this exploit was fixed in 1.1, we still have global storage, and things which we can try, if anything will not work i will open the IDA, and unlock the io and os module and become the god

https://youtu.be/79T4Gp0RlfY?si=ANJt-2HNXt7teXb8

someone actually did it using TAS:
https://www.reddit.com/r/factorio/comments/g8vsqs/factorio_018_toolassisted_speedrun_wr_12120/

let's add LLMS to do this thing, and make them compete in the speedrun


https://www.reddit.com/r/factorio/comments/13cbgco/first_step_in_creating_an_ai_to_play_factorio/
