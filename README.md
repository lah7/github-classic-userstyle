
# "Classic" CSS for GitHub

This repository contains my personal CSS modifications for [github.com](https://github.com).

It tries to keep elements of the past design alive using CSS, such as:

* More compact layout, less roundness.
* Restore older font weights and colours in commit lists.
* Use monospace for extended commit messages.
* Use older sizes for avatars.
* Hide excessive titles.

Some minor enhancements are made, like:

* Using native checkboxes.
* Sticky comment headers while scrolling an issue/PR.

It won't restore the old UI or layouts, and it can't restore any older UX
or speed up the 'modern' AJAX calls. Rather, it tries to keep the older
feel alive as GitHub keeps advancing towards React.

Like GitHub's design is considered "opinionated", these are also opinionated tweaks
to make GitHub a little more comfortable for me, and maybe for you too!

**The CSS is optimised for:**

- Dark theme.
- Logged in users.
- Opting out of new experiences (e.g. Issues/Pull Requests) until it has been completely rolled out.


## Updates

I've been personally patching the CSS using Stylus since around 2020 when GitHub
first began to ~~regress~~ replace UI/UX parts with React.

The code was moved into a repository here so I can easily sync changes between my
home and work computer.
