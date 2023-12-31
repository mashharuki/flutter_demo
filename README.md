# flutter_demo_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## CLIでのプロジェクト生成

```bash
flutter create hello_world
```

## 動かし方

```bash
flutter run
```

実行結果

```bash
This app is linked to the debug service: ws://127.0.0.1:49889/xsF_LtBzXmQ=/ws
Debug service listening on ws://127.0.0.1:49889/xsF_LtBzXmQ=/ws

💪 Running with sound null safety 💪

🔥  To hot restart changes while running, press "r" or "R".
For a more detailed help message, press "h". To quit, press "q".

An Observatory debugger and profiler on Chrome is available at: http://127.0.0.1:49889/xsF_LtBzXmQ=
Flutter Web Bootstrap: Programmatic
The Flutter DevTools debugger and profiler on Chrome is available at: http://127.0.0.1:9100?uri=http://127.0.0.1:49889/xsF_LtBzXmQ=
Application finished.
```

ポート番号を指定して起動する場合

```bash
flutter run --web-port 8080
```

開発プラットフォームを指定する場合

```bash
flutter run -d all
```
