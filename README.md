# Who is me?
```kotlin
data class Me(
    val name = "Haruto Kato",
    val role = "Android Engineer",
    val company = "BizReach, Inc.",
    val lang = mapOf(
        "Japanese" to "C2",
        "English" to "B2",
    ),
)
```

# 🎉Conference Speaker 
## DroidKaigi 2026
URL: [「アクセシビリティを利用するとき、アクセシビリティもまたこちらを利用している」 〜マルウェアによる攻撃と防衛について〜](https://2026.droidkaigi.jp/timetable/1229693/)

I talked about cybersecurity specializing in malware abusing accessibility.

## KotlinFest 2026
URL: [Kotlin × グラフ理論：Unstable APIで挑む関数レベルAffected Test Selectionライブラリ](https://2026.kotlinfest.dev/sessions/session-15)

I talked about the `astra` series.  
I also explained how we can apply graph theory to the field of Affected Test Selection by utilizing `Kotlin Analysis API standalone`.

# 🚀Open Source Software
## [sazamai](https://github.com/sazanami-lab/sazanami)
<p align="start">
    <a href="https://plugins.gradle.org/plugin/io.github.mikhailhal.sazanami"><img src="https://img.shields.io/gradle-plugin-portal/v/io.github.mikhailhal.sazanami?style=flat-square&logo=gradle&label=Gradle%20Plugin" alt="Gradle Plugin Portal"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square" alt="License"></a>
    <a href="https://kotlinlang.org"><img src="https://img.shields.io/badge/Kotlin-2.1.20-7F52FF.svg?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin"></a>
    <a href="#"><img src="https://img.shields.io/github/actions/workflow/status/MikhailHal/sazanami/ci.yml?style=flat-square&logo=github" alt="CI"></a>
<br>

It analyzes your code changes and identifies which tests are affected, enabling faster feedback loops by running only the tests that matter.

## [ariadne](https://github.com/sazanami-lab/ariadne)
<p align="start">
    <a href="https://github.com/MikhailHal/ariadne/releases"><img src="https://img.shields.io/github/v/release/MikhailHal/ariadne?style=flat-square&color=success" alt="Release"></a>
    <a href="https://registry.modelcontextprotocol.io/v0/servers?search=io.github.MikhailHal/ariadne"><img src="https://img.shields.io/badge/MCP%20Registry-listed-6E56CF.svg?style=flat-square" alt="MCP Registry"></a>
    <a href="https://github.com/MikhailHal/homebrew-tap"><img src="https://img.shields.io/badge/homebrew-mikhailhal%2Ftap-FBB040.svg?style=flat-square&logo=homebrew&logoColor=white" alt="Homebrew"></a>
    <a href="https://github.com/MikhailHal/ariadne/pkgs/container/ariadne"><img src="https://img.shields.io/badge/ghcr.io-ariadne-2496ED.svg?style=flat-square&logo=docker&logoColor=white" alt="Container image"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square" alt="License"></a>
    <a href="https://kotlinlang.org"><img src="https://img.shields.io/badge/Kotlin-2.3.0-7F52FF.svg?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin"></a>
</p>

It is an MCP (Model Context Protocol) server that provides AI agents with the ability to identify affected tests.  
Powered by [sazanami](https://github.com/MikhailHal/sazanami), it analyzes code changes and returns only the tests that need to be run.
