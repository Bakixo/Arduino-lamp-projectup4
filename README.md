# Arduino-lamp-projectup4
The lamp that we can turn on and off melodiously with button and butter






int led = 8;                                  
int sound = 3;                              

void setup()
{
   pinMode(led, OUTPUT);               
   pinMode(sound, OUTPUT);         
}

void loop()                                         
{
   digitalWrite(led, HIGH);               
   tone(sound, 1000, 250);             
   delay(2000);                                  
   digitalWrite(led, LOW);              
   tone(sound, 6000, 250);             
   delay(2000);                                
}
