# GMCv2-Shooting-Component
Expansion of the General Movement Component V2 hitscan demo, incorporating core features for shooting as well as basic projectile support.

Features:

* Support for firing projectiles as well as hitscan
* Can fire multiple "bullets" per shot (eg. shotgun)
* Fire rate
* Multiple firing input modes - semi auto, full auto, hold to charge then release, and hold to charge with a damage increase over a charge threshold.
* Shot spread - random (within a threshold), increased spread with each shot (with a gradual decrase over time), or fixed spread (only works properly with multiple shots per fire input

Known Issues:

* Client fires multiple sets of shots. Seems to be mostly cosmetic and server is mostly unaffected.
