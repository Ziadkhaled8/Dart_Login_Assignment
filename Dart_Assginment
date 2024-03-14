import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: Text('Login Screen App')),
        body: Center(child: LoginScreen()),
      ),
    );
  }
}

class LoginScreen extends StatefulWidget {
  @override
  _LoginScreenState createState() => _LoginScreenState();
}

class _LoginScreenState extends State<LoginScreen> {
  @override
  Widget build(BuildContext context) {
    return Column(
      mainAxisAlignment: MainAxisAlignment.center,
      children: <Widget>[
        Text('Welcome', style: TextStyle(fontSize: 24)),
        SizedBox(height: 20),
        TextField(decoration: InputDecoration(labelText: 'User Name')),
        TextField(
          decoration: InputDecoration(labelText: 'Password'),
          obscureText: true,
        ),
        SizedBox(height: 10),
        Align(
          alignment: Alignment.centerRight,
          child: TextButton(onPressed: () {}, child: Text('Forgot Password')),
        ),
        ElevatedButton(onPressed: () {}, child: Text('Login')),
        Row(mainAxisAlignment: MainAxisAlignment.center, children: <Widget>[
          Text("Don't have an account?"),
          TextButton(onPressed: () {}, child: Text("Sign Up")),
        ]),
      ],
    );
  }
}
