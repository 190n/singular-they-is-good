# singular-they-is-good

This is an advanced bitrate calculator written in Bash. It determines the length of a media file and calculates the required bitrate for it to fit within a given number of bytes.

## Dependencies

- mediainfo
- bc

## Installation

Download the script, make sure it is executable, and put it somewhere in your `$PATH`.

## Example usage

```
$ singular-they-is-good ten-seconds.mkv 5000000
4000000.00000000000000000000
```

This shows that to fit a 10-second video in 5 MB, the bitrate can be up to 4 Mb/s.
