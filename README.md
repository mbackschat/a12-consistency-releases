# A12 consistency checker

Kernel-free model consistency checks for Kotlin and Java, released under the MIT license. This checker has partial coverage: ALL_CHECKS_PASSED means its implemented checks passed; it does not establish that A12 would accept the model. Reports retain complete: false and disclose gaps.

## Gradle (Kotlin Multiplatform or JVM)

```kotlin
repositories {
    maven("https://mbackschat.github.io/a12-consistency-releases/maven/")
    mavenCentral()
}
dependencies {
    implementation("io.github.mbackschat.a12.dm:dm-consistency:0.14.0")
}
```

Gradle selects the JVM or JS variant. Java/Maven consumers use the same repository URL and io.github.mbackschat.a12.dm:dm-consistency-jvm:0.14.0. The matching dm-predicates coordinates are transitive dependencies. JVM requires Java 21 or newer.

[Checker sources](https://mbackschat.github.io/a12-consistency-releases/maven/io/github/mbackschat/a12/dm/dm-consistency/0.14.0/dm-consistency-0.14.0-sources.jar) · [Release assets](https://github.com/mbackschat/a12-consistency-releases/releases/tag/v0.14.0)

This mirror provides Maven artifacts only. npm and Maven Central publication are not part of this release.
