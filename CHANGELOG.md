# Change Log

### 0.2.17
* `rdp` => `static defaultProps = { }`
* `rpt` => `static propTypes = { }`

### 0.2.16
* `rwwd` should not have a constructor, nor initialize state
* `est` empty state type is now an exact type

### 0.2.15
* Props are now exact types

### 0.2.14
* Change functional stateless snippets to create a named function, rather than arrow syntax

### 0.2.12
* Remove PropTypes from component snippets.  I mean, we are using Flow, right?  I've left the standalone PropTypes snippets in, as I'm sure there's some edge case that I'm missing

### 0.2.0 

* Update lifecycle method snippets to prompt user for Props & State type
* Correctly populate Props & State types for Component snippets