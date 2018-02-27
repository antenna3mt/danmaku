# Danmaku

A live commenting system for interactive events on a large scale. Event participators send comments by cell phone to a large screen lively.

## Functionality

1. Participators send comments on cell phone with preferred color.
2. Event managers review the comments and are free to approve or discard them
3. Event managers can close the review function and approve all comments
4. Multi-users are allowed
5. Display-end fetches the comments and display them on screen. Comments can be on the top layer and overlap other contents on screen.

## Try Demo

### Push comments online:

[Danmaku-web](http://danmaku.solidmatrices.com)

Login Token: cc123456

### Display comments offline

Download executable jar [Danmaku-display](https://github.com/antenna3mt/danmaku-display/blob/master/danmaku_display.jar)

Connect Token: dd123456

Click "Connect"

 - Click "Fetch" to fetch the comments from remote server.
 - Click "Test" to test the functionalities.
 - Click "Push" to push comments.

**Multi-screen for better experience**

## Technical Stuff

### Participator-end & Manager-end

Web application; React-Redux-dva

[Github: danmaku-web](https://github.com/antenna3mt/danmaku-web)

### Display-end

JavaFX2

[Github: danmaku-display](https://github.com/antenna3mt/danmaku-display)

### Server-end

API server; golang

[Github: danmaku-server](https://github.com/antenna3mt/danmaku-server)

### Communication

Jsonrpc 2.0

