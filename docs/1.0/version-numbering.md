# Version Numbering

Beginning with the [relaunch of Flipside as a social media platform for next-gen creators](), we are moving to a simplified versioning system and calling that release 1.0 to signify the new direction the app is taking, from a virtual TV studio into a complete platform for creators to share their spatial content creations with the world.

We keep version numbers in sync across our suite of products.

> Previously, we used a [Calendar Versioning](https://calver.org/), or CalVer.

## Let's look at an example

```
1.0-stable
```

This breaks down into the following elements:

* `1` - The major version of the software.
* `0` - The minor release version within the major version, starting at zero.
* `stable` - The release stage suffix, in this case denoting that this is a stable release.

Each beta that follows a stable release will increment either the major or minor release number, depending on whether the beta includes major or minor/incremental changes.

Release numbers only increase after a release is marked `-stable`. Prior to that, the beta or release candidate number is denoted after the release stage suffix, e.g., `-beta1`, `-beta2`, etc.

Valid suffixes include `-alpha#`, `-beta#`, `-rc#`, and `-stable`, although in practice alpha releases are internal only.

### More examples

Here are a series of examples as the version numbers increment with new updates:

* `1.0-beta1`
* `1.0-beta2`
* `1.0-beta3`
* `1.0-rc1`
* `1.0-rc2`
* `1.0-stable`
* `1.1-stable`
* `1.2-stable`
* `2.0-beta1`
* Etc.
