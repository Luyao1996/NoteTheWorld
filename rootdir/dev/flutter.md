











### dart.exe损坏处理方案：
Remove-Item -Recurse -Force E:\luyao\flutter\bin\cache
$env:FLUTTER_STORAGE_BASE_URL="https://storage.flutter-io.cn"
$env:PUB_HOSTED_URL="https://pub.flutter-io.cn"
flutter doctor