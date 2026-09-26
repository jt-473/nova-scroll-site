# Nova scroll story

A scroll-driven product page. As you scroll, a 222-frame image sequence plays forward, and scrolling back up plays it in reverse. Five text screens animate in and out over the footage.

## Run it locally

```bash
python3 -m http.server 5173
```

Then open http://localhost:5173.

## Files

- `index.html`: the page. Frames are drawn on a canvas as you scroll.
- `frames/`: the 222 JPEG frames the page scrubs through
- `poster.jpg`: social share preview image

All copy and figures are placeholders.

## Credits

- Visual style and several effects adapted from [React Bits](https://github.com/DavidHDev/react-bits) by David Haz (MIT + Commons Clause), ported to vanilla JS.
- Design pass guided by [taste-skill](https://github.com/Leonxlnx/taste-skill).
- Icons: [Phosphor](https://phosphoricons.com). Fonts: [Geist](https://vercel.com/font).
