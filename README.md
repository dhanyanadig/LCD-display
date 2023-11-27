#include<LiquidCrystal.h>
LiquidCrystal led(19,23,18,17,16,15);

void setup(){
  led.begin(16,2);
  led.print("Hello world...");

}
void loop()
{
  led.setCursor(3,1);
  led.print("By Dhanya");

}
