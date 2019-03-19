![#TigerChat](https://user-images.githubusercontent.com/29003194/54636209-4d8c5580-4a5c-11e9-8bf6-0a0d11387862.png)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Fast, modern chat application built with Node.js and socket.io
**Takes seconds to get started!**
  - Built upon https://github.com/wayou/HiChat with improvements to core functionality and design.

## Notable improvements/changes:

  - Fixed top frame navigation issue with original HiChat application
- Function to convert 24-hour time to 12-hour time
- Changed wording to better reflect functions and reduce confusion by the end user
- Added styling to buttons
- Added styling to login page
- Streamlined emoji support
- Rules to prevent chat abuse
- Limit to how large an image can be


> Forked from HiChat with the intention to bring modern design and more features to it.

### Installation / Setup Instructions

TigerChat requires [Node.js](https://nodejs.org/) v4+ to run.

1. Install the dependencies and start the server.

```sh
$ npm install
$ node server
```

1. If you're using io.js

```sh
$ npm install
$ iojs server
```

2. Open your browser and visit 'localhost:3000'.
3. Sign in and test!

### Future Improvements

 - Modal images to allow users to click and see a bigger version of images
 - Add night mode
 - Support for more than one chat room
 - List users instead of just listing amount of online users

License
----

MIT


