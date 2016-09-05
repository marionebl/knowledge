# Developer Experience

Simply put user experience principles applied to all things development.

Really hard nuts to crack in this problem space:

*   Performance. Build and development setups are slow and blocking.
*   Abstraction and Magic Sauce. It is hard to hit the right level of abstraction.
*   Lock-in. Developers are wary of lock-in effects and reject any notion of non-conventionalism.
*   Die-hard work flows

## Techniques

### Keyboard shortcuts

Developers are affine to keyboard-only usage of tools.
Simple keyboard shortcuts with sequences up to three make users faster.
See [ux.stackexchange.com](http://ux.stackexchange.com/a/30749)

### Hot module replacement

Introduced by webpack into the JavaScript landscape.
Best in class REPL experience when things do not go wrong.
Has issues with error handling.
Kills source debugging because there is `eval`ing going on.
See [browserfiy-hmr](https://github.com/AgentME/browserify-hmr)

### Remote debugging protocol sourcing

Some JS runtimes are converging on the Chrome Remote Debugger Protocol.
There is API for injecting sources into the runtime.
Retains source debugging.
Not widespread yet. See [amok](https://github.com/amokjs/amok)

## Tools

*  [Webpack](https://github.com/webpack/webpack)
*  [browserfiy-hmr](https://github.com/AgentME/browserify-hmr)
*  [amok](https://github.com/amokjs/amok)
