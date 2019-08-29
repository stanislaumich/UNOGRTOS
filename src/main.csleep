#include <Arduino.h>
// **** INCLUDES *****
#include "LowPower.h"
int state=0;
void setup()
{
  // No setup is required for this library
  pinMode(LED_BUILTIN,OUTPUT);
  digitalWrite(LED_BUILTIN,state);
}

void loop() 
{
  // Enter idle state for 8 s with the rest of peripherals turned off
  // Each microcontroller comes with different number of peripherals
  // Comment off line of code where necessary

  // ATmega328P, ATmega168
  LowPower.powerDown(SLEEP_1S, ADC_OFF, BOD_OFF);  


  // Do something here
  // Example: Read sensor, data logging, data transmission.
  state==0?state=1:state=0;
  digitalWrite(LED_BUILTIN,state);
}

