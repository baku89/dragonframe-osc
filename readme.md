# dragonframe-osc

An integration of Dragonframe and OSC.

## Setup

### 1. Install dependencies of Node.js

```
npm install
```

### 2. Set the `dragonframe-script.js` as a action script from the preferences of Dragonframe

![](./dragonframe-pref.png)

## Format

This script send osc when some events (such like frame moved, pressed shutter, and completed to shoot) triggered. The address is `/dragonframe/(event-name)`, and it has a single integer value represents a current frame in Dragonframe.

For more details, please reference at this [shell script](http://www.dragonframe.com/dragonframe_script.sh.txt).


## License

The MIT License (MIT)
Copyright (c) 2016 Baku Hashimoto

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.