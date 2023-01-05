import 'package:flutter/material.dart';

void main() =>runApp(MaterialApp(
  home: portfolio(),
));
class portfolio extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.grey[900],
      appBar:AppBar(
        title: Text('Portfolio'),
        centerTitle: true,
        backgroundColor: Colors.grey[850],
        elevation: 0.0,
      ) ,
        body:Padding(padding: EdgeInsets.fromLTRB(30.0, 40.0, 30.0, 0),
        child: SingleChildScrollView(
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.start,
            children: [
              Image.asset('assests/images/1photo.jpg'),
              SizedBox(height:30),
              Text(
                'NAME ',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),
              ),
              SizedBox(height: 10.0),
              Text(
                'ANURAG CHAUHAN ',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,
                ),

              ),
              SizedBox(height: 30.0),
              Text(
                'EDUCATION DETAILS ',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
              SizedBox(height: 10),
              Text(
                'B.TECH FIRST YEAR (CSIT)',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,

                ),

              ),
              SizedBox(height: 30),
              Text(
                'SKILLS ',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
           SizedBox(height: 10),
              Text(
                'LEARNING C',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20 ,
                  fontWeight: FontWeight.bold
                ),

              ),
           SizedBox(height: 30),
              Text(
                'COLLEGE ',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
            SizedBox(height: 10),
          Text(
          'KIET GROUP OF INSTITUTIONS ',
          style: TextStyle(
            color: Colors.white,
            letterSpacing: 2.0,
            fontSize: 20,
            fontWeight: FontWeight.bold,
          ),

      ),
       SizedBox(height: 30),
          Text(
            'ADDRESS ',
            style: TextStyle(
              color: Colors.white,
              letterSpacing: 2.0,

            ),

          ),
          SizedBox(height: 10),
              Text(
                'GORAKHPUR U.P.',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,
                ),

              ),
          SizedBox(height: 20),
              Text(
                'ABOUT ME',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
            SizedBox(height: 10),
              Text(
                'TECH ENTHUSIAST',
                  style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,
                ),

              ),
            SizedBox(height: 30),
              Text(
                'CONTACT DETAILS',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
            SizedBox(height: 10),
              Text(
                ' EMAIL',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 10,
                  fontWeight: FontWeight.bold,
                ),

              ),
              Text(
                ' anuragchauhan4444@gmail.com',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,
                ),

              ),
            SizedBox(height: 15),
              Text(
                ' MOB.NO.',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,

                ),

              ),
              Text(
                '7007607446',
                style: TextStyle(
                  color: Colors.white,
                  letterSpacing: 2.0,
                  fontSize: 20,
                  fontWeight: FontWeight.bold,
                ),

              ),
            ],
          ),
        ),
      ),
    );
  }
}



