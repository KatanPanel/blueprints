# blueprints
Blueprints are models used to determine how an instance, a component of its [terminology](https://katan.org/docs/getting-started/ecosystem), will be built.

* [Introduction](#introduction)
* [How to Contribute](#contributing)

## Introduction

Created from files in [HOCON format](https://github.com/lightbend/config/blob/main/HOCON.md), blueprints definitions will later be transformed into instances, these files are **verified and published in this repository not containing any sensitive data or malicious purpose**, of course, if they are not used in private scope.

Here's a minimal example:
```ini
name = "My Awesome Blueprint"
version = "1.0.0"

remote {
    origin = "https://github.com/KatanPanel/blueprints"
}

build {
    image = "busybox"
}
```

The above example demonstrates the following features of blueprints:
* **Semantic Versioning**: Blueprints must follow the [semantic versioning standard](https://semver.org/).
* **Remote Tracking**: Blueprints can be imported from remote sources so Katan users will not be limited to blueprints created from themselves.

## Contributing

Before you start contributing remember that **this repository is public and used by Katan** so always
remember this when doing something during your contribution that is not just beneficial to you but also in a general
context.

[Click to read the contribution guidelines](https://github.com/KatanPanel/blueprints/blob/main/CONTRIBUTING.md).
