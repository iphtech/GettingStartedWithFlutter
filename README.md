Section 1
$ flutter doctor


Section 2
| Flutter (Channel beta, v0.1.5, on Mac OS X 10.12.6 16G1212)
| Android toolchain - develop for Android devices (Android SDK 27.0.2)
| iOS toolchain - develop for iOS devices (Xcode 9.2)
| Android Studio (version 3.0)
| IntelliJ IDEA Community Edition (version 2017.1.3)
| Connected devices (2 available)


Section 3
$ flutter create flutter_hello_world


Section 4
flutter_hello_world
android
ios
lib
main.dart
test


Section 5
import 'package:flutter/material.dart';
void main() => runApp(new HelloWorldApp());
class HelloWorldApp extends StatelessWidget {
@override
Widget build(BuildContext context) {
return new MaterialApp(
home: new Material(
child: new Center(
child: new Text("Hello world!"),
),
),
);
}
}


Section 6
$ flutter run
$ flutter run -d DEVICE_ID
$ flutter run -d all
