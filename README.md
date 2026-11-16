# aho-corasick in Kotlin

[![GitHub link](https://img.shields.io/badge/GitHub-KotlinMania%2Faho--corasick--kotlin-blue.svg)](https://github.com/KotlinMania/aho-corasick-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kotlinmania/aho-corasick-kotlin)](https://central.sonatype.com/artifact/io.github.kotlinmania/aho-corasick-kotlin)
[![Build status](https://img.shields.io/github/actions/workflow/status/KotlinMania/aho-corasick-kotlin/ci.yml?branch=main)](https://github.com/KotlinMania/aho-corasick-kotlin/actions)

This is a Kotlin Multiplatform transliteration port of [`BurntSushi/aho-corasick`](https://github.com/BurntSushi/aho-corasick) (`aho-corasick 1.1.4`).

**Original Project:** This port is based on [`BurntSushi/aho-corasick`](https://github.com/BurntSushi/aho-corasick). All design credit and project intent belong to the upstream authors; this repository is a faithful port to Kotlin Multiplatform with no behavioural changes intended.

---

## About this Kotlin port

### Installation

```kotlin
dependencies {
    implementation("io.github.kotlinmania:aho-corasick-kotlin:0.1.0")
}
```

### Building

```bash
./gradlew build
./gradlew test
```

### Targets

- macOS arm64
- Linux x64 / arm64
- Windows mingw-x64
- iOS arm64 / simulator-arm64 (Swift export + XCFramework)
- tvOS / watchOS
- JS (browser + Node.js)
- Wasm-JS (browser + Node.js) & Wasm-WASI (Node.js)
- Android (API 24+) & Android Native x64 / arm64

### License

Dual-licensed under the Unlicense or MIT license, matching upstream [`BurntSushi/aho-corasick`](https://github.com/BurntSushi/aho-corasick). See [LICENSE-MIT](LICENSE-MIT) and [UNLICENSE](UNLICENSE).
