# What's this

This is a AC  source for Swift language.
![screenshot 1](screenshots/sc-01.png)

Japanese description is [here](http://ponpoko1968.hatenablog.com/entry/2015/11/09/183855)

# prerequisites

- json.el
- sourcekitten
  This AC source uses sourcekitten command.
  install [sourcekitten](https://github.com/jpsim/SourceKitten).


# Install 
```
(require 'auto-complete-swift)
(push 'ac-source-swift-complete ac-sources)
```
# Configuration

Set swift-compiler-args to appropreate '--compilerargs' argument of sourcekitten commandline.

# Thanks

[mikeandmore/auto-complete-clang](https://github.com/mikeandmore/auto-complete-clang)

[chrisbarrett/swift-mode](https://github.com/chrisbarrett/swift-mode)

[jpsim/SourceKitten](https://github.com/jpsim/SourceKitten)

# Copyright
 
Copyright (c) 2015 Shuji OCHI, released under the MIT license  


