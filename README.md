# Engineeringproject

## Description
My project is a egg crusher. A bladed axe is placed on top of a box on a acrylic plate. When you hit the button it swings down and hits the egg which is on its own stand.

## Timeline 

April 15th-I started my own project
May 20th- I completed the build for my project
May 28th-I completed the code for my project.

## Psuedo code
//sketch created by Akshay Joseph follow me on Instagra: five_volt_player

include<Servo.h>
Servo Myservo;
int pos=0;
void setup()
{
  pinMode(2,INPUT);
  Myservo.attach(3);
}

void loop()
{
  if(digitalRead(2)==LOW){
    Myservo.write(180);
  }
  else
    
 Myservo.write(0);

}


## Finished circuit

![image](https://user-images.githubusercontent.com/71350259/121247742-98c6f480-c870-11eb-80e4-fb3a347019d6.png)

## Final Assembly

![image](https://user-images.githubusercontent.com/71350259/121248615-a335be00-c871-11eb-8a58-0cde3f834e7d.png)
Full project
![image](https://user-images.githubusercontent.com/71350259/121248703-bcd70580-c871-11eb-97ad-64446531c799.png)
This is the axe used to crush the egg.
