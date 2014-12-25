homebrew-chromium
=================

Chromium Snapshots Delivered Through Homebrew!

------

How do I tap this repository?
--------------------------------
Just `brew tap domt4/chromium`.

It really is that simple. Yay! Fresh Chromium delivered regularly. Like bread, but less edible.

--------------------------------

Yes, the [Caskroom/Brew-Cask](https://github.com/caskroom/homebrew-cask) does this sort of thing too.

However, when I created this repository they distributed the Portable, Flash-enabled version of Chromium and I didn’t want or need that.

In early November the Caskroom switched to using the direct downloads from the Appspot blog, but due to the nature of these downloads the Caskroom also disabled checksumming of that file for integrity, and I’d rather not punt that kind of risk when rocking a browser. 

The Caskroom’s formula also makes it extremely difficult for people to remain on up-to-date Chromium versions, as Chromium ships with no built-in update method.

My method here allows myself or anyone to go back upstream, check the commit reference, download that binary zip themselves and checksum it if desired.

In the end, I’ve traded convenience for very slightly greater security, and I accept that compromise. If anyone else desires to, this repository is here for all.

This tap will never be used for anything other than Chromium. 

This repository previously used a mirror, but the upstream link actually seems to work properly with cURL now, so we are officially using the correct upstream link! Hurrah, no more mirroring!

For fun: When I started this repository on October the 8th 2014 Chromium was on Commit Number 298608. Compare that to where we are today (!).
