# Flutter-miniproject
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
      home: NehaCard(),
    ));

class NehaCard extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.grey,
      appBar: AppBar(
        title: Text('Institute ID Card'),
        centerTitle: true,
        backgroundColor: Colors.black,
        elevation: 0.0 ,
      ),
      body: Padding(
        padding: EdgeInsets.fromLTRB(30.0, 40.0, 30.0, 0.0),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: <Widget>[
            Center(
              child: CircleAvatar(
                backgroundImage: AssetImage('assets/images/Neha1.jpg'),
                radius:60.0,
              ),
            ),

            Divider(
              height:90.0,
              color:Colors.white,
            ),
          Text(
          'NAME',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
            )
          ),
          SizedBox(height: 10.0),
          Text(
          'Neha Singh',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
              fontSize: 28.0,
              fontWeight:FontWeight.bold
            )
          ),
          SizedBox(height: 30.0),
          Text(
          'Institute ID',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
            )
          ),
          SizedBox(height: 10.0),
          Text(
          '202151098',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
              fontSize: 28.0,
              fontWeight:FontWeight.bold
            )
          ),
          SizedBox(height: 30.0),
          Row(
            children:<Widget> [
              Icon(
                Icons.email,
                color:Colors.white,
                ),
                SizedBox(width:10.0),

                Text(
                  '202151098@iiitvadodara.ac.in',
                  style: TextStyle(
                  color: Colors.white,
                  fontSize: 18.0,
                  letterSpacing:1.0,
                  ),
                ),
            ],
             ),

          SizedBox(height: 30.0),
          Text(
          'Institute Name',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
            )
          ),
          SizedBox(height: 10.0),
          Text(
          'Indian Institue of Information technology Vadodara',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 1.0,
              fontSize: 22.0,
              fontWeight:FontWeight.bold
            )
          ),

          SizedBox(height: 30.0),
          Text(
          'BRANCH',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
            )
          ),
          SizedBox(height: 10.0),
          Text(
          'Computer Science',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,
              fontSize: 22.0,
              fontWeight:FontWeight.bold
            )
          ),
        ],

        ),

      ),
    );
  }
}
  
![ID_CARD(Flutter)](https://user-images.githubusercontent.com/121671988/214217876-832c661b-4143-4dd0-a40d-dc756448ee85.jpg)
  
  
  
  

