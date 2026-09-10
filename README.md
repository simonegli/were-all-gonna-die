# We’re all going to die

Every recorded warning that thinking machines will end us, from the steam age to this week, on one sideways-scrolling wall.

**Live:** see the Vercel deployment. **Source:** `index.html`, a single file with no build step.

## Add a voice

Every entry is one line in the `EVENTS` array in `index.html`:

```js
{t:2023.24, c:"thinker", q:"Shut it all down.", who:"Eliezer Yudkowsky, TIME", then:"Proposed airstrikes on rogue data centres. Nobody did that either."},
```

- `t` is a decimal year: year + (month − 1) / 12 + (day − 1) / 365.
- `c` is one of `fiction`, `thinker`, `builder`, `politics`.
- `q` is an exact quote, or a one-line paraphrase with `para:1`.
- `who` names the person and the venue. `then` is one dry sentence about what happened next.

Only add entries you can source. Open a pull request with the line and a link to the source.

## Run locally

Open `index.html` in a browser, or serve the folder with `python3 -m http.server`.
