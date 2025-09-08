# CrateVersioning
A repo showing how Cargo crate versioning works.

It shows the following two things:

1. Pre-release versioning follows https://doc.rust-lang.org/cargo/reference/manifest.html#the-version-field:

`A pre-release part can be added after a dash such as 1.0.0-alpha. The pre-release part may be separated with periods to distinguish separate components. Numeric components will use numeric comparison while everything else will be compared lexicographically. For example, 1.0.0-alpha.11 is higher than 1.0.0-alpha.4.`,

and not 

https://doc.rust-lang.org/cargo/reference/specifying-dependencies.html#pre-releases:

`Cargo allows “newer” pre-releases to be used automatically.`


2. As new versions are published, the ["wrapper"](./wrapper/) picks it up