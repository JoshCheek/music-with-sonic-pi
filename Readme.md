Make music with Ruby
====================

Install [Sonic Pi](http://sonic-pi.net/#mac).
Looks like it's a `.dmg` so you can probably just run it,
but if it ultimately gives you a "Sonic Pi.app" file (might not display the ".app"),
then drag it to the "/Applications" directory.

These commands assume you're in the same directory as the code.
Start the Sonic Pi server (we send the music to it for playing).

```sh
$ ./run-server
```

Execute it with:

```sh
# play music.rb
$ ./play

# play some other song
$ ./play my-other-song.rb

# play from stdin
$ echo 'play 60' | ./play -
```

Attribution
-----------

* Code based on [Sonic Pi Cli](https://github.com/Widdershin/sonic-pi-cli)
* Sonic Pi's [Source Code](https://github.com/samaaron/sonic-pi) referenced on occasion.

License
-------

The MIT License (MIT)

Copyright (c) Josh Cheek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
