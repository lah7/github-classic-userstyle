
# "Classic" CSS for GitHub

This repository contains my personal CSS modifications for [github.com](https://github.com).

It tries to keep elements of the past design alive using CSS, such as:

* More compact layout, less roundness.
* Restore older font weights and colours in commit lists.
* Use monospace for extended commit messages.
* Use older sizes for avatars.
* Hide excessive titles.

Some minor enhancements are made, like:

* Using native checkboxes/radios.
* Sticky comment headers while scrolling an issue/PR.

It won't restore the old UI or layouts, and it can't restore any older UX
or speed up the 'modern' AJAX calls. Rather, it tries to keep the older look &
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


## Screenshots

### Code View
| Before | After |
| ------ | ----- |
| ![Code - Before](https://github.com/user-attachments/assets/26e94aa2-bd49-409a-a25f-35d87ddd72d0) | ![Code - After](https://github.com/user-attachments/assets/72e23c26-7837-41d5-95a5-d1b713162c6f) |

### Commit List
| Before | After |
| ------ | ----- |
| ![Commits - Before](https://github.com/user-attachments/assets/cabc19da-bc27-4ce0-b898-f428dd318d21) | ![Commits - After](https://github.com/user-attachments/assets/b9956623-579a-4483-bc0d-c15d77f07bdf) |


## Updates

Since around 2020 when GitHub first began ~~regressing~~ changing the UI design,
I began using Stylus to patch things back to something more comfortable.

I figured to make this code public in 2025 after the
[general availability of the new Issues and Projects](https://github.blog/changelog/2025-04-09-evolving-github-issues-and-projects/),
plus I'd like to easily sync updates between my home and work computer.

If/when GitHub changes the UI and I encounter it, I'll update the style as soon as I can.
