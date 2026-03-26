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

### ios generate_certs

```sh
[bundle exec] fastlane ios generate_certs
```

Locally generate code signing certificates using the API Key

### ios pr_build

```sh
[bundle exec] fastlane ios pr_build
```

Push a new beta build to TestFlight PR group

### ios beta_dev

```sh
[bundle exec] fastlane ios beta_dev
```

Push a new beta build to TestFlight Main group

### ios release_prod

```sh
[bundle exec] fastlane ios release_prod
```

Push a new release build to TestFlight

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
