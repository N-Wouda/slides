# Slides

This repository hosts code for several presentations I've given/intend to give.
I use [`reveal-md`](https://github.com/webpro/reveal-md) to turn my Markdown files
into web-based presentations using [`reveal.js`](https://revealjs.com/).

Assuming you have `reveal-md` installed, any presentation here can be built 
using
```
reveal-md <path to .md file> -w
``` 
from the project root **in the `src` branch**. All presentations are under 
`slides/`, each in their own directory. This particular command watches the 
file, and opens the web browser to the presentation that updates as the markdown
file is updated.

# Deploying

Made simple using the `prepare_deploy.sh` script in the repository root. After
preparing to deploy, the `src` and `gh-pages` branches still need to be pushed.
That's up to you - I'm not a fan of autocommit modes.
