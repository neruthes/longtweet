# Long Tweet

## Use

Visit <https://joyneop.xyz/longtweet/>.

## Payload

This software work un the assumption that `location.search` would start with `?t=001`, where `001` is the version number of the payload.

- Encode: Use native `window.escape` function and process other unsafe characters (which do not fit in `[\%\w\d\-\_\+]`) by replacing them with `'%' + char.codePointAt(0)`.
- Decode: Use native `window.unescape` function.

## Math

For the sample essay in English, it added 74% extra characters to be URL-safe. The 1496-character essay became the 2608-character URL.

## Copyright

© 2019 Neruthes <neruthes.xyz>

Licensed under [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).
