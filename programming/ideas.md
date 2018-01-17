# Ideas

Ideas for project, libraries and features to implement

## Work in progress
* [ ] configurable `commitlint` bot: https://github.com/ahmed-taj/commitlint-bot
* [ ] dedicated git editor. poc at https://github.com/marionebl/git-editor

## Done
* [x] Animated SVG renderer for [asciinema](https://github.com/asciinema/asciinema-player) for usage in Github markdown. https://github.com/marionebl/svg-term-cli

## Tools

* [ ] Styleguide creator interface for [patternplate](https://github.com/sinnerschrader/patternplate)
* [ ] Blueant interface (think Google Calender Week View)
* [ ] **lerna-dashbaord**: Webinterface for meta information connected to lerna repos
* [ ] `travis-bot`: Generic bot that triggers Travis CI builds for (configurable) `pull-request.*` events. Could be implemented by using a worker-queue repository, where tasks are pushed to that in turn trigger TravisCI runs.
* [ ] `vscode-commitlint`: vscode plugin providing inline linting and intellisense for commit messages
* [ ] Grammar-based, extensible commit parser. First thoughts: https://github.com/conventional-changelog/conventional-changelog/issues/238
* [ ] Build svg version of https://github.com/dawnlabs/carbon
* [ ] `pkg-lint`: Lint `package.json` for plausibility, check deps, presence of used npm bins, presence of main and bin entries, etc. 
* [ ] `asciinema-studio`: Software to trim, cut, edit asciicast recordings
* [ ] `asciinema-script`: Markup language to declare automated terminal (input) sequences 

## Libraries

* [ ] **react-term**: React renderer for terminals striking the middleground between [ink](https://github.com/vadimdemedes/ink) and [mylittledom](https://github.com/manaflair/mylittledom) Should support flexbox layouts, event delegation. Might take inspiration from https://github.com/ksandin/react-surface
* [ ] **default-css**: Mapping between tag names and applicable default styles. Automate as much as feasible. Reference: [html5](https://www.w3.org/TR/html5/rendering.html#replaced-elements), [webkit](https://trac.webkit.org/browser/trunk/Source/WebCore/css/html.css), [gecko](https://dxr.mozilla.org/mozilla-central/source/layout/style/res/html.css)

## Features

* [ ] **patternplate**: Network visualization of pattern dependencies
* [ ] **@commitlint/prompt**: Inline editing interface
* [ ] **@commitlint/prompt**: Explanations for fields
* [ ] **@commitlint/core**: Perform automatic fixes
* [ ] **Rust**: Add `shadowed-let` as lint check to rustc

## Obsolete
* [ ] ~~[**bankai**](https://github.com/yoshuawuyts/bankai/issues/31) Hot Module Replacement~~
* [ ] ~~dependency-checker bot skimming through npm packages proactively, producing PRs~~ https://renovateapp.com/
