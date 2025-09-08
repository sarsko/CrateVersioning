# Hiya

The documentation for pre-releases is ambiguous, stating both (from https://doc.rust-lang.org/cargo/reference/specifying-dependencies.html#pre-releases):

`Cargo allows “newer” pre-releases to be used automatically.`

and also (from https://doc.rust-lang.org/cargo/reference/manifest.html#the-version-field)

`A pre-release part can be added after a dash such as 1.0.0-alpha. The pre-release part may be separated with periods to distinguish separate components. Numeric components will use numeric comparison while everything else will be compared lexicographically. For example, 1.0.0-alpha.11 is higher than 1.0.0-alpha.4.`

This crate tests which one is true.