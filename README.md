![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=kbot&fontSize=90&animation=fadeIn)
**Disclaimer** If you get banned it is not my fault, this is a use at your own risk program.


[Old Version Video](https://kb.likes-to-co.de/n8hzdfry.mp4)

## Please create issue requests with the new feature label to request features

# kbot

kbot is an AI aimbot that utilizes the yolov7 detection model. The `normal.py` file displays a window with the detection rendering, while the `streamer.py` file runs without displaying the window, resulting in slightly faster performance.

Currently the mouse movements are not functioning in VALORANT but it will still work as a triggerbot.

In the two weeks I've tested this on CS:GO I have not been banned.

The files with V serve as prototypes for achieving smooth and consistent adjustments. When executed, they prompt the user to choose between two options: 1 (shoot) and 2 (do not shoot). Option 1 provides a reasonably smooth aiming experience, with shooting (Set delay so may not be perfect for some weapons). Option 2 offers slightly better aiming performance than the option 1 version, but the shooting functionality is unimplemented.

[![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fkbdevs%2Fai-aimbot&count_bg=%239279B5&title_bg=%23555555&icon=&icon_color=%23FFFFFF&title=Views&edge_flat=false)](https://hits.seeyoufarm.com)

# TODO
- Refine aim
- Release ESP
- Polish/Make a GUI


# How to 
[tutorial](https://github.com/kbdevs/ai-aimbot/assets/86767129/dda5a2f0-89b7-4cb8-9332-a61588bc0123)



# FAQ

## Which games is kbot compatible with?

kbot is expected to work with games that have player models resembling human anatomy.

## How can I use kbot?

**Due to the valorant bypass I implemented you need to make sure there are no windows in the way of the image grabber, make sure the detection window sees just the game, you can check using a `normal` version.

To configure kbot for your desired game, simply modify the window title within the provided Python code. By default, it is set to work with CS:GO, but changing it should enable compatibility with other games, **make sure the game is windowed/windowed fullscreen**. Once executed and a player is detected, pressing and holding the assigned key (modifiable) will cause kbot to aim and shoot at the detected players, without differentiating between teams, I would recommend using this more as an assist, it works but not enough that in high stakes you don't need to move your mouse.

## How do I make it use GPU?
![image](https://github.com/kbdevs/ai-aimbot/assets/86767129/4231cfa3-6a3f-485e-aaa7-ef7a78680ae8)
[You can use this guide.](https://medium.com/analytics-vidhya/build-opencv-from-source-with-cuda-for-gpu-access-on-windows-5cd0ce2b9b37) 


## I need assistance!

Feel free to reach out to me via Discord at @kb.kb or create a github issue request

© Catch Me If You Can Industries
