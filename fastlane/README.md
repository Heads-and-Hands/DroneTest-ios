fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios create

```sh
[bundle exec] fastlane ios create
```

Create a new application on the developer portal

### ios register

```sh
[bundle exec] fastlane ios register
```

Register devices on apple portal

### ios test

```sh
[bundle exec] fastlane ios test
```

Perform test checks

### ios internal

```sh
[bundle exec] fastlane ios internal
```

Deploy a build for beta testing

### ios release

```sh
[bundle exec] fastlane ios release
```

Deploy a release build

### ios bootstrap_cocoapods

```sh
[bundle exec] fastlane ios bootstrap_cocoapods
```

Install cocoapods dependencies

### ios refresh_dsyms

```sh
[bundle exec] fastlane ios refresh_dsyms
```

Download and refresh dsyms

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
