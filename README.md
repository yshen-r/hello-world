import 'package:flutter/material.dart';

void main() => runApp(MyApp());
  


class MyApp extends StatelessWidget{
  @override 
  Widget build (BuildContext context){
    return MaterialApp(
        title:"Fit4U",
        home: Scaffold(
          appBar: AppBar(
            title: Text("Help Page"),
            ),
            body: ContentWidget(),
            ),
    );
  }
}

class ContentWidget extends StatelessWidget{
  @override
  Widget build(BuildContext context){
    return Text(
      "I cant login Fit4U, what should I do \nPlease check your username and password. If they are correct, you might close Fit4u and try it again for one or two times. If you canot login, please contact our staff. \nI cant sign in Fit4u, how can I do \nPlease check your personal information. if it still doesnot work, you can close it and retry."
    );
  }
}
