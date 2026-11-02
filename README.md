**License update**: from version 0.95 the whole game, including media, is **CC0**. The assets were replaced by ones released under CC0.

![screens](https://github.com/drummyfish/bombman/blob/master/resources/logo.png?raw=true)

FOSS Bomberman clone!

## Requirements

* Python 3.8 or newer (tested on Python 3.14)
* [pygame-ce](https://pypi.org/project/pygame-ce/) 2.5.0 or newer (the maintained fork of pygame, imported as `pygame`);
  upstream `pygame` 2.0.0 or newer works as well

## Installing and running

```
pip install -r requirements.txt
python bombman.py
```

The game refuses to start on pygame 1.x and prints the command above, since it
relies on SDL2 event types and key codes that only exist from pygame 2 on.

![screenshot](http://i.imgur.com/3xbgAPM.png)

Early developmnet Video:

[![preview](http://img.youtube.com/vi/N1pGgX_rFOQ/0.jpg)](http://www.youtube.com/watch?v=N1pGgX_rFOQ "preview")
