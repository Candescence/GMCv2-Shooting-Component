# GMCv2-Shooting-Component
Expansion of the General Movement Component V2 hitscan demo, incorporating core features for shooting as well as basic projectile support.

Incorporates a weapon structure and class system for multiple weapon types that can be easily swapped over the network. This does not include swapping weapon models and VFX, but implementing it in your projects should be straightforward.

I consider this feature-complete and don't plan to tinker with this further (outside of specific implementations in my own projects). 

Features:

* Support for firing projectiles as well as hitscan (line trace and sphere trace)
* Can fire multiple "bullets" per shot (eg. shotgun, does not support random spread)
* Fire rate
* Multiple firing input modes - semi auto, full auto, hold to charge then release, and hold to charge with a damage increase over a charge threshold.
* Shot spread - random (within a threshold, works only with single shot), increased spread with each shot (with a gradual decrase over time, works only with single shot), or fixed spread (only works with multiple shots per fire input)
* Changing any arbitrary number of weapons

Known Issues:

* Projectiles 'nudge' client pawns and bots slightly, including client players firing shots.
* Unable to properly sync random spread with simulated shots. In practice this is a minor issue that is unlikely to be noticed by players in most cases, and has no effect on actual gameplay.
