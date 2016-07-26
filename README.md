# Stick_for_Blind--Arduino-
This for Helping who are blind or visually impaired.to help find obstacle in there way . 

Hardware :- 
     1.  Arduino Uno or any other 
     2.  UltraSonic sensor HC-SR04
     3.  A stick
     5.  Vibrator Motor (in this project am using a vibrator from  old phone )
     6.  BUzzer 
     7.  LED (optional)
     


Software  :-
     1.  Arduino IDE


Step 1:- 
  
       
        Arduino pin Digital 12  to trigger pin on the ultrasonic sensor.
        Arduino pin Digital 11 to echo pin on the ultrasonic sensor.
        Arduino pin +5v to Vcc pin on the ultrasonic sensor.
        Arduino pin GND to GND pin on the ultrasonic sensor.

        buzzer +ve pin  to Arduino Digital Pin 13 
        buzzer -ve pin  to Arduino GND
  
        Vibrator +ve pin to Arduino Digital Pin 13
        Vibrator -ve pin to Arduino GND

        //if you want to connect the LED just conncet the LED like Buzzer;
  
  

Step 2:-

       
        Upload the Code into Arduino via Arduino IDE
  
        Change the Distance Limit As your Need , Just Change "if(uS / US_ROUNDTRIP_CM <10)"  10 insted of your value .

Step 3:-
       
       place  all the hardware in to the stick and the vibrator part in need to be in hand , because that will help to give better happtic feed back about the obstacle in the way.
       
       place the ultrasonic sensor into front of the stick
       

Step 4:-
        
      Power up the arduino 
  
  
  The blind Stick is Complete :-D , if any obasacle in front of the blinder the vibrator will be active and the vibration will get and same time the buzzer will ON , 
  
  importent :- "The Responce will work in the basis if the Limit that we set in the code "
  
