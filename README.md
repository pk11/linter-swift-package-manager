##  linter-swift-package-manager

This package will lint your .swift opened files in Atom through Swift Package Manager (SPM).

Use bits and pieces from [linter-swiftc](https://github.com/AtomLinter/linter-swiftc) (thank you @kepler0!)

## Installation
```
$ apm install linter-swift-package-manager
```

## Settings

You can configure linter-javac by editing `~/.atom/config.cson` (choose Open
Your Config in Atom menu):

```coffeescript
"linter-swift-package-manager":
  # The path to Swift.   
  executablePath: "/usr/bin/swift"
```