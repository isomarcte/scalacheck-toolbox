---
layout: docs
---

# Get started

Any issues, suggestions or criticisms are more than welcome.

For SBT, you can add the relevant dependency to your project's build file:

[comment]: # (Start Replace)
```scala
resolvers += Resolver.sonatypeRepo("releases")

"com.47deg" %% "scalacheck-toolbox-datetime" % "0.2.5" % "test"

"com.47deg" %% "scalacheck-toolbox-magic" % "0.2.5" % "test"

"com.47deg" %% "scalacheck-toolbox-combinators" % "0.2.5" % "test"
```

[comment]: # (End Replace)