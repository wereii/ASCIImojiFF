# ASCIImojiFF

This is "port fork" of https://github.com/hpcodecraft/ASCIImoji for Firefox

### What? Why?

Bascially I wanted to leave chrome but this masterpiece extension was the last thing that kept me there.

### What is different

- just a code, extension itself acts the same
- to summarize the code change:
    - upgraded use jQuery from 2.1.1 to 3.4.1 (luckilly the asciimoji jquery plugin seems to still work)
    - `chrome` API calls changed to `browser` and edited for comaptibility
    - `manifest.json` ported for Firefox (70.0)
