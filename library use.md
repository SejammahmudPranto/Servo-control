#include<Servo.h>

Servo servo;

const int angle;
void setup() {
  servo.attach(7);
  servo.write(angle);
  
  // put your setup code here, to run once:

}

void loop() {
  int angle=180;
  servo.write(angle);
  delay(500);
  servo.write(0);
  delay(500);
  // put your main code here, to run repeatedly:

}
