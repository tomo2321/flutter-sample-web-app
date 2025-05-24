# sample_web_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Installation Memo

```shell
git clone $repo_url
cd $repo_name
fvm use $flutte_version --force
rm .gitignore
# [fvmを使ってFlutterプロジェクトを作成する #Terminal - Qiita](https://qiita.com/kilalabu/items/7ed07a99024e1687a8f4)
fvm flutter create . --project-name sample_web_app --platforms web --org com.samplewebapp
echo -e '\n# FVM Version Cache\n.fvm/\n' >> .gitignore
mkdir .vscode && echo -e "{\n\"dart.flutterSdkPath\": \".fvm/versions/$flutter_version\"\n}" > .vscode/settings.json
```
