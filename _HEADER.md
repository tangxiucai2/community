![Flutter Community](https://raw.githubusercontent.com/fluttercommunity/community/master/banner.png)

# Flutter Community
**A central place for all community made Flutter packages.**

---

The Flutter Community is a GitHub organisation used to manage community made Flutter packages.

Our goal is to ensure packages made by the Flutter community are kept alive and maintained in one place.

## Medium Articles
To go along with the packages, we have started a Medium publication as a central location for community content to be published - especially if it relates to the packages here.

https://medium.com/flutter-community

# Packages
These are the packages featured on the Flutter Community.

<PACKAGETABLE>

# Submitting your packages
If you want your packages to be included in the Flutter Community organization, make sure you have read and completed the following steps.

<!--
## Guidelines
 - Android and iOS compatible
 - Package is published and approved on Dart pub.
 - ...
-->

## Preperation
In order for the Flutter Community organization to keep track of all the submitted packages and their maintainer, all repositories are required to contain a `pubspec.yaml` file **in the root of the repository**. This file contains information about the package, pub page and maintainer.

**Note, without this file your package will not be listed in the [packages table](#Packages).**

### How to setup your pubspec file.
Please make sure your project's `pubspec.yaml` file contains a field named `maintainer` that contains the maintainer's name and GitHub username (usually your name and username) in the following pattern:
```yaml
...
maintainer: YOUR-NAME (@YOURGITHUBUSERNAME)
...
```

#### Example

Your `pubspec.yaml` file should look something like this (example taken from [after_layout](https://github.com/fluttercommunity/flutter_after_layout)):
```yaml
name: after_layout
description: Execute code after the first layout of your widget has been performed, i.e. after the first frame has been displayed.
version: 1.0.7
authors:
 - Flutter Community <flutter-community@googlegroups.com>
 - Simon Lightfoot <simon@devangels.london>
homepage: https://github.com/fluttercommunity/flutter_after_layout
maintainer: Simon Lightfoot (@slightfoot)
```

## Getting in contact
If you've [prepared your packages](#-Preperation), you can either:
- **RECOMMENDED**: [Open an issue on the `community` repository.](https://github.com/fluttercommunity/community/issues/new)
- Contact us in the Study Group.

### Note to packages owners
Flutter Community aims to bring the best community-made packages forward. Because of this, not all proposed packages will be accepted.

Do you have a package you want submitted that delivers the same or similar functionality as an existing package? Please [contact us](##-Getting-in-contact) or contact the maintainer of the package on Flutter Community.
