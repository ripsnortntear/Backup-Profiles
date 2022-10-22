# Eureka Notorious Monster Farming

These profiles are designed to pop Notorious Monsters (Eureka's name for Fates) and kill them in an effort to help you gain the materials necessary to earn your Eureka relic weapons.

These profiles are meant more to be an assistant rather than a complete AFK profile. You're going to want to keep track of what NMs have been killed so you know when they're available to be killed again.

I recommend using https://ffxiv-eureka.com/ to keep track of which Fates are ready to be spawned again.

## Setup

Before you start, open the profile and set a NM to 1. This will cause the bot to target the mobs that spawn that NM until the NM spawns and will then fight the NM.
The profile will go down the list targeting from top to bottom anything set to 1. It will not detect if any fates have spawned in the zone.
So if you have to stop the profile it will start back at the top when you start it again. To avoid that, set anything you kill to 0.

There's also setting for announcing the Fate in Shout for the zone and a setting to stop the bot immediately after shouting. This is for use when you're in a populated Eureka instance and want to announce the fate to allow other people to join you. Once you're ready to kill the fate, just start the bot again and it'll start the encounter.
It's considered proper Eureka etiquette to allow others to join in on the Fate. Besides, a lot of them are too hard to solo.

You will also need to install the latest version of [LlamaLibrary](https://github.com/nt153133/__LlamaLibrary). Make sure you update LlamaLibrary before running the profiles, Kayla is constantly making new tags for this set and you'll need the absolute latest.

I'm in the process of changing over all the movement in this profile to be handled by Lisbeth. Saga's new Sextant 2.0 is far superior to anything else RebornBuddy has to offer and makes for a much smoother questing experience. As such, you will need Lisbeth to make these profiles work. If you don't have it, you can find it here: https://www.siune.io/
