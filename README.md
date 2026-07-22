<div align="center">

# 👋 Welcome to my profile!

### Android Engineer / OSS Developer

静的解析でテスト時間を改善するライブラリをつくっています！！

</div>

> [!NOTE]
> 最近はTOEFLに追われててあまりコードが書けてません……！！！！！！！🥲

<br>

## My OSS

<br>

### 🤖 [ariadne](https://github.com/MikhailHal/ariadne) — AIエージェントに *Affected Test* を渡すMCPサーバー

<a href="https://github.com/punkpeye/awesome-mcp-servers"><img src="https://img.shields.io/badge/Featured_on-awesome--mcp--servers-FF6B6B?style=flat-square&logo=awesomelists&logoColor=white" /></a>
<a href="https://registry.modelcontextprotocol.io/v0/servers?search=io.github.MikhailHal/ariadne"><img src="https://img.shields.io/badge/MCP_Registry-listed-6E56CF?style=flat-square" /></a>
<a href="https://github.com/MikhailHal/ariadne/stargazers"><img src="https://img.shields.io/github/stars/MikhailHal/ariadne?style=flat-square&color=success" /></a>

AIエージェントがコードを編集した後、「今の変更で走らせるべきテストはどれ？」に秒で答えるMCPサーバー、後述するsazanamiを解析エンジンとして再利用しています。  
Google製リファレンスアプリ [Now in Android](https://github.com/android/nowinandroid)（34モジュール）で実測し、**約4秒 / テストクラス選択率 25 of 27** を確認しています。

> 🎉 **世界のMCPサーバーを集めた [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) に掲載されました**
> （公式 MCP Registry / Glama にも登録済み）

<br>

### 🌊 [sazanami](https://github.com/MikhailHal/sazanami) — Kotlin向け Affected Test Selection エンジン

<a href="https://github.com/MikhailHal/sazanami/stargazers"><img src="https://img.shields.io/github/stars/MikhailHal/sazanami?style=flat-square&color=success" /></a>
<a href="https://plugins.gradle.org/plugin/io.github.mikhailhal.sazanami"><img src="https://img.shields.io/badge/Gradle_Plugin-Portal-02303A?style=flat-square&logo=gradle&logoColor=white" /></a>

ariadneの心臓部。
Kotlin Analysis API を使って関数・プロパティ・コンストラクタ・メソッド参照まで含めたコールグラフを構築し、逆方向にたどって影響テストを特定します。  
CI向けのGradle Pluginとしても提供していますが、偽陰性の保証が困難なためあまり推奨していません！

<br>

## 🎤 Tech Conference Experience

- 🗣️ **DroidKaigi 2026** — 2026/9/1~9/3 「アクセシビリティを利用するとき、アクセシビリティもまたこちらを利用している」 〜マルウェアによる攻撃と防衛について〜
- 🗣️ **Shibuya.apk** — 2024/10/11 Androidを自由にカスタマイズしたい〜！
