# naf-css
## Not Another [css] Framework

[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdgrammatiko%2Fnaf-css.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdgrammatiko%2Fnaf-css?ref=badge_shield)

## What is this?
Obviously **not** another CSS framework. If you need a CSS framework you're in the wrong place, navigate away immediately!
This is a glorified normalise.css with some twists:
- It is based on PostCSS
- It is utilizing CSS Custom Properties
- It **doesn't** come with an opinionated/outdated grid system. Use CSS Grid Layouts!
- The code is split into critical and lazy parts. The critical parts should be inlined into your page's headers and the lazy parts should be, wait for it, lazy loaded (eg after DOMContentLoaded).
- The code is distributed in several files which represent the HTML elements or components. This, theoretically, should make it really easy to style everything without rewriting a framework...
- The build script is provided as a showcase. You **should** style the elements/components to your flavour and compile **only** the needed files.
- It is utilizing [sanitize.css](https://github.com/csstools/sanitize.css)
- Inspired by [hiq](https://jonathanharrell.github.io/hiq/) and all the great CSS Frameworks


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdgrammatiko%2Fnaf-css.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdgrammatiko%2Fnaf-css?ref=badge_large)