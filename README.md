# Signal Lab

A tiny interactive network experiment. Find the corrupted nodes, repair them, and watch the signal come back online.

**Play it: <https://juliangonzalez-tech.github.io/signal-lab/>**

It's a playful companion to my [GitHub profile](https://github.com/juliangonzalez-tech). Real AI reliability is a lot messier than seven pink dots; this is only a visual metaphor.

## Details

- A single static `index.html`: no build step, no dependencies, no tracking.
- Keyboard accessible (Tab to a node, Enter or Space to repair it), with visible focus rings and a live status message.
- Touch-friendly 44 px targets and a layout that works from phone to desktop.
- Respects `prefers-reduced-motion`: the ambient background is drawn once instead of animating.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
