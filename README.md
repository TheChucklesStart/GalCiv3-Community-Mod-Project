# GalCiv3-Community-Mod-Project
It seems to me that eventually we will have mod races for many sci-fi and fantasy shows, and many new races that came from the imaginations of their creators.

Having watched many mods in the past for games never quite reach the fully playable point, I am somewhat worried that we will end up having 15 Federation implementations which are all 75% complete.

I had the idea that maybe we should get together and use something like github or bitbucket to organize a massive mod where we can each put in our own mods (focused on new races and the things to support them) when we feel they are ready, and the community can merge, update and balance them so that they fit in with all of the other races in the game and mod.

This would also allow us to handle the case where the master xml files need to be changed (such as the case for allowing unmodded custom races to use the new homeworlds) without conflicting so that we can have a game with the borg aligning themselves with the mandelorians to fight the peacekeepers and enslave the cylons only to have the achieve ascension.

To this effect, I was thinking that our mod might have the following (incomplete and example) structure:

Master Mod Directory
   |
   |-- Common Mod Data  (where homeworld and other shared assets live, and everyone touches everything fairly often)
   |
   |-- Popular Universes (where races from popular universes are created, and many people have hands in creating, balancing and updating them)
   |      |
   |      |-- Star Trek Universe
   |      |      |
   |      |      |-- Federation
   |      |      |
   |      |      |-- Klingon Empire
   |      |
   |      |-- Star Wars Universe
   |             |
   |             |-- The Empire
   |             |
   |             |-- The Rebellion
   |
   |-- User Open Domain Races  (where people have put their own creations, but feel alright with other people balancing and adding to them)
   |      |
   |      |-- AwesomeGal123
   |      |      |
   |      |      |-- NeatRaceOfFun
   |      |
   |      |-- CoolDude456
   |
   |-- User Closed Domain Races (where people have put their own creations, but they may not be ready for others to start messing with them yet)
          |
          |-- ControlFreak15
          |      |
          |      |-- SuperDetailedOrganisms
          |
          |-- WorkInProgressCreator9

This seems like one of the easiest ways to ensure that my dream of destroying a borg cube with the death star becomes a reality.