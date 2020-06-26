# 4chancapper
4chan Capper is a plugin for Firefox and Chrome that is designed to be a tool for you to use, to help with "capping" threads.

## Why develop this?
Because I got tired of manually either removing all unwanted posts for that perfect cap, or having to fuck around with gimp
just to cap a thread.

## Image sizes, cap sizes?

Every option will ask you first (NO EXCEPTIONS) if you want it to be 4chan compatible or not. (under Settings, you can
check "Do not ask me, make every operation 4chan compatible)" and it won't ask you every time).
4chan compatible is 4 MB, and no larger than 5000x5000
If you choose not to, then there really is no limit. The tool will make sure to cap every post etc at full size.
For legibilitys sake, only the OP's first post has no horizontal limit.
Everyone elses posts will be squashed down to be under 600 px so they are symmetrical with eachother.
One word replies will have their background extended to 600 px for parity.
In settings, you can have any post containing less than 10 words be minimized, as if you had used alternative 6.

## HALP WHAT DO THE VARIOUS THINGS DO?

1: Vertical Capture (all posts)
This alternative will capture all the posts in the thread, and automatically resize the captured posts if needed to fit into
a 1000 pixel X 5000 Pixel image. If the tool cannot make text legible (legible is no less than 80% of the actual size of the captured post, see FAQ)
on any post, it will prompt you to use alternative number 3 instead, alternatively, you can choose to only use the first 150 replies.


2: Vertical Capture (selected)
Same as above, but only selected posts are capped.

3: Grid Capture (Auto)
This option will first prompt you if you want to capture selected posts or ALL.
Regardless of what you choose, the plugin will automatically try to select a appropiate column and row size


4: Grid Capture (Auto)
Same as above, but you get to manually choose the column and row size. It will still automatically resize posts if needed to ensure symmetry etc.

5: Extract Images of posts
This alternative will get the full size and thumbnails of a post as their own seperate images. They are named after the post number itself
to make it easier to know which stuff belongs to which post.

6: Extract Words as Images
This alternative is a bit special. Select the posts you want to extract words from.
Then choose this alternative. You will now be guided to select (one at a time) each passage (or word etc) of
text from the selected images. You can select from the same post several times (you will need to press
Once that is done, you will be prompted for how large you want the words to be. It is inspired by this image
https://imgur.com/Y2ZyGcT where they copied "EXPLAIN SPURDO" and "THREAT MATRIX".

## FAQ YOU!

Q: In HALP, it's mentioned that "legible is no less than 80% of the actual size of the captured post", why cannot we modify this ourselves?
A: Because fucking nobody likes a idiot that does shit caps of threads where the text is unreadable unless you use a magnifying glass. Fuck that shit. This tool enforces that text atleast be legible. You could be a dick and edit images later but that's on you. Download the damn source code and edit it yourself 
if you must have it. I am not going to help you with it.

Q: Does this work on phones?
A: No, it will detect phones and promptly tell you to go fuck yourself, this is because the plugin is dependent upon
posts being their full size on a desktop and at their highest "resolution" and work from there, you also won't be able to browse any webpage at all
until you uninstall it from your phone. Perhaps in the future.
Try to install the plugin more than 3 times on a phone and it will delete everything in the DCIM folder on your phone and redirect you to
lemonparty.org, you have been warned. (And don't try to be a smartass and use web agent modifiers on desktop, it does have a case against that)-

Q: In relation to the above question, can't you use some sort of emulator or remote request.
A: I could but I won't. Not for now.

Q: Internet Explorer?
A: GO fuck yourself. Port this shit on your own if you want it. I will not touch that even with a 10 foot pole.

Q: Why GIMP for alternative 9?
A: It's free
