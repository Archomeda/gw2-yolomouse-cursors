# Guild Wars 2 cursors for YoloMouse

Anybody who has played Guild Wars 2, has probably come across the problem where you lose track of your mouse cursor. Maybe not as frequent as me, but most likely at least once.
If you're frustrated by this, then using [YoloMouse](https://pandateemo.github.io/YoloMouse/) is an option, in combination with these modified Guild Wars 2 cursors.
Be sure to read the [YoloMouse tutorial](https://pandateemo.github.io/YoloMouse/help.html) about how to add custom cursors, which will not be explained here.

This repository contains various cursor packs that you can use in combination with YoloMouse.
You can find those in the 'cursors' folder.

If you want, you can create your own pack by taking the images from the 'originals' folder.
An easy way to create cursor files is by using [RealWorld Cursor Editor](http://www.rw-designer.com/cursor-maker).
If you have created your own cursor pack, please share them by submitting a pull request.

Please note that I do not own the copyright of both the original images and the modified ones; the copyright will always belong to ArenaNet.
I provide these images to the community for free, in the hope that it will help some people to keep track of their mouse cursor.

## Downloads
You can download the whole repository by pressing the 'Download ZIP' button at the top right corner of this page.
Or, alternatively, you can click [here](https://github.com/Archomeda/gw2-yolomouse-cursors/archive/master.zip).
This way you get the cursors all at once, and you don't have to download one by one.

After downloading, grab your favorite cursor pack and add the cursors to YoloMouse ([follow the YoloMouse tutorial](https://pandateemo.github.io/YoloMouse/help.html)).
Note that by default, you can only use one pack at a time.
You can mix packs by renaming the cursor files to something unique (or replace other cursors).

## Troubleshooting
- *I don't want to go through the effort of assigning all the cursors myself!*
<br>
Well, you're lucky.
YoloMouse saves the cursor assignment on your hard drive.
And we can share that.
<br>
In your `%LOCALAPPDATA%\YoloMouse` folder, there should be a file called after Guild Wars 2, something like `*__Gw2_exe.ini` or `*__Gw2_64_exe.ini` where the asterisk can be anything.
Open it, copy the contents of the 'assignments.txt' file of your favorite cursor pack, and paste it in this .ini file. Replacing everything else.

- *I can't assign any cursors in the 64-bit client, how can I get YoloMouse to work?*
<br>
Apparently there seems to be an issue for some people that can't get the cursors to work in the 64-bit client.
As mentioned in [this reddit post](https://www.reddit.com/r/Guildwars2/comments/3xlakx/customized_guild_wars_2_cursors_for_yolomouse/cy5sfos?context=10000), you can solve this issue by hovering over the patcher window, and pressing `Ctrl + Alt + Shift + 1`.
After the game has started up, repeat this.
You can now assign the custom cursors to the Guild Wars 2 cursors.

- *Whatever I try to do, the cursor size doesn't match the original Guild Wars 2 ones*
<br>
If this happens, then you might have a cursor pack with an odd cursor size (anything that isn't a multiple of 32x32).
Apparently, YoloMouse can't scale it properly by default, which leads to either bigger (and pixelated) cursors, or smaller cursors compared to the original cursors.
To solve this, scale the cursor down until it resets to its actual pixel size by pressing `Ctrl + Alt + Shift + -` repeatedly.
