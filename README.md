# CHAPTER-3

5. Create Your First Flutter App
Create a Project:
Use the following command in the terminal:
flutter create my_first_app

Run the App:
Start your app using:
flutter run
This launches the app on the connected emulator or device.

6. Understand Flutter's Project Structure
lib/main.dart: Entry point of the Flutter application.
Sample Code
Here’s a basic Flutter "Hello World" app:

import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Hello Flutter'),
        ),
        body: Center(
          child: Text(
            'Welcome to Flutter!',
            style: TextStyle(fontSize: 24),
          ),
        ),
      ),
    );
  }
}


