
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


## Installation

1. Install [Stylus for Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or [Stylus for Chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne).
2. [Add the style](https://github.com/lah7/github-classic-css/raw/refs/heads/master/github-classic.user.css) and click "Install Style".
  * This will populate the "update URL" field.

If you use another compatible extension that appends CSS to the page, add this URL:

    https://github.com/lah7/github-classic-css/raw/refs/heads/master/github-classic.user.css


## Updates

I've been patching the CSS using Stylus since around 2020 when GitHub first
began to ~~regress~~ replace UI/UX parts with React.

The code was moved into a repository here so I can easily sync changes between my
home and work computer, and now public if you're like me and miss elements of the
old GitHub.

If GitHub changes the UI and I spot it, I'll update the style as soon as I can.
