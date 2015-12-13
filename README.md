# Screaming Liquid Tiger

Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder.

I wrote this because I wanted an easy way to use [Overcast](https://overcast.fm/) to listen to my audiobooks. Podcast players are ideal applications for this, contrary to generic media players. It is also trivial to be adapted to other uses and file types.

* Automatically gets media files from same folder, no fiddling with a GUI
* Automatically sets file modification date
* Automatically sets per-file MIME type
* Automatically sets file size
* Generates valid RSS and Atom feeds for maximum compatibility

## Installation and Usage

Just upload the `index.php` file to a folder on a web server running PHP 5.4 or higher. Edit the configuration variables if needed and upload media files of any kind. For personal podcasting use, those should obviously be audio files but you can use it with any kind of file.

## Changelog

### 0.1.1

* Some restructuring and clean up.
* More code comments.

### 0.1.0

* Inital release.

## License

The MIT Licence

Copyright © 2015 Marcel Bischoff

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.