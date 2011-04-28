# Keycounter

![](http://stillmaintained.com/programble/keycounter.png)

A keystroke counter for X11.

## Usage

    Usage: keycounter [OPTION]... [FILE]
    
      -f, --follow          output keypress statistics as they update
      -d, --daemonize       run in the background
      -p, --pid-file=FILE   write PID to FILE
      -h, --help            display this help and exit

If `FILE` is not present, write keypress statistics to standard output.

## Example Output

    You pressed 545 keys in 10 minutes, 45 seconds
    You pressed 0.84 keys per second
    You pressed 50.70 keys per minute
    You pressed 3041.86 keys per hour
    You pressed 73004.65 keys per day

## License

Copyright (c) 2011, Curtis McEnroe <programble@gmail.com>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
