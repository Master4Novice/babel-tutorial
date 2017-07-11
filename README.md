# Babel

Babel is a JavaScript compiler.

# Install the Babel CLI and a preset

npm install --save-dev babel-cli babel-preset-env

# ES2015 and beyond
These plugins allow you to use new syntax, right now without waiting for browser support.

npm install --save-dev babel-preset-env

# Polyfill
Since Babel only transforms syntax (like arrow functions), you can use babel-polyfill in order to support new globals such as Promise or new native methods like String.padStart (left-pad).Use it by requiring it at the top of the entry point to your application or in your bundler config.

npm install --save-dev babel-polyfill

# JSX and Flow
Babel can convert JSX syntax and strip out type annotations.Use it together with the babel-sublime package to bring syntax highlighting to a whole new level, and add "react" to your .babelrc presets array.

npm install --save-dev babel-preset-react

# Pluggable
Babel is built out of plugins. Compose your own transformation pipeline using existing plugins or write your own.

# Debuggable

Ref : http://babeljs.io/docs/setup/#installation for installation.
