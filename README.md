# TablePaste

This is a palette for Mathematica that makes it easy to paste tabular or JSON data into Mathematica notebooks.  For a full description, see

 * http://szhorvat.net/pelican/pasting-tabular-data-from-the-web.html

To use this palette, download the `.paclet` file from the [releases page][1] and [install it][2] using the `PacletInstall` function.  It is not necessary (or recommended) to clone this repository unless you want to read or modify the source code.

## Known issues

 - On macOS, using the palette for the first time in a session may cause the Mathematica Front End to lose focus and the palette to disappear. This does not affect functionality. Simply click into any notebook window to re-gain focus.

## Revision histroy

#### Version 1.0.1

 - Remove trailing empty lines from tables
 - Fix incompatibility with RLink on macOS

#### Version 1.0.0

 - Initial release

 [1]: https://github.com/szhorvat/TablePaste/releases
 [2]: http://mathematica.stackexchange.com/q/141887/12
