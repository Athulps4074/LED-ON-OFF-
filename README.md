 void setup() 
{
   pinMode(10,OUTPUT);   
  pinMode(3,INPUT);  
}

void loop() 
{
  if (digitalRead(3)==LOW)
    {digitalWrite(10,HIGH);}  
else 
    digitalWrite(10,LOW);   
  }
