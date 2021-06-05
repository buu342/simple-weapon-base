# Simple Weapon Base (S&Box)
A community managed simple to use weapon base for S&amp;Box

## Goal
During the lifetime of garrysmod many weapon bases consisting of poor quality were created. The goal is to offer an easy to use yet very configurable weapon base maintained by the community for the community.

## Installing
If you want to test out the base just drag and drop simple-weapon-base-master into your addons folder.

## Features

### Various
* No programming skills needed to use
* Highly configurable
* Support for custom animations and actions

### Built-in Animations
* Walking
* Zooming
* Running
* Idle

### Bases
* Magazine (default)
* Shotgun (shell based reloading)
* Melee

### CSS Weapons
* CSS weapons are included to showcase the base usage
* They will get their own repo later down the line when more guns are ported
* Feel free to use them for your own gamemodes

## Contributing
Anyone can contribute by creating a pull request to their branch. Contributors can help out with the planned updates, outstanding bug/issues, or maybe you just have a cool idea that would improve the base, any help is welcome!

## Planned Updates
* Framerate independent animations
* Jumping animation
* Looking animation
* Empty clip sound
* Sniper base
* Entity base (e.g. shooting arrows)

## Current Bugs
* While running looking up or down will force weird rotations on the run animation
* In multiplayer world models are positioned weird for others (possible engine bug)
* Multiplayer has an object null reference error
  * WeaponBase.cs, Line 326: `if ( !string.IsNullOrEmpty( clipInfo.MuzzleFlashParticle ) )`
  * Could be cause by incorrect networking of clipInfo