# virtualbox with limiting for images

To securely operate virtualbox in a controlled environment I would
like to be able to give people a build that only imports images that I
say are ok.

That means:

* no create image
* checking all imported images somehow are ok


I also want:

* no gui (because everyone's using vagrant)


This repository is my hacks on virtulabox to make that work.


## links and detail

to build:

* [Vbox linux build instructions](https://www.virtualbox.org/wiki/Linux%20build%20instructions)
* make sure you disable hardening to do dev builds, otherwise you can't run directly from build
* builds end up in out/linux.amd64/release/bin

