# GMCv2-Shooting-Component
Expansion of the General Movement Component V2 hitscan demo, incorporating core features for shooting as well as basic projectile support.

Incorporates a weapon structure and class system for multiple weapon types that can be easily swapped over the network. This does not include swapping weapon models and VFX, but implementing it in your projects should be straightforward.

Features:

* Support for firing projectiles as well as hitscan (line trace and sphere trace)
* Can fire multiple "bullets" per shot (eg. shotgun)
* Fire rate
* Multiple firing input modes - semi auto, full auto, hold to charge then release, and hold to charge with a damage increase over a charge threshold.
* Shot spread - random (within a threshold, works only with single shot), increased spread with each shot (with a gradual decrase over time, works only with single shot), or fixed spread (only works properly with multiple shots per fire input)
* Changing any arbitrary number of weapons

Known Issues:

* Projectiles 'nudge' client pawns and bots.