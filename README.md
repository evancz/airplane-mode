# Airplane Mode

Airplanes are programming heaven. Going on a 10+ hour flight is a recipe for extraordinary focus and productivity. I always get off these flights feeling good and having done some cool shit. I wanted that without the plane though.

Airplane Mode turns off the distracting parts of the internet, so you can read docs but not get on Facebook, Twitter, Gmail, etc.

![Picture](picture.png)

Just click it to toggle between airplane mode and normal.


## Install

All you need is the `Airplane\ Mode.app` part. So get this repo as a zip and grab it.

From there just click the icon to toggle things on and off.


## Customize

This works by messing with your `/etc/hosts` file. The [`on`](Airplane%20Mode.app/Contents/Resources/on) and [`off`](Airplane%20Mode.app/Contents/Resources/off) files determine how things work. You can just edit them. Add or remove websites to the list depending on your bad habits.

You can get to these files pretty easy too. Just right click the icon and go to "Show Package Contents". That will let you get at all the relevant files in Finder.

![Customize](customize.png)