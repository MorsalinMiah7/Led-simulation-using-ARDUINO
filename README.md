# Led-simulation-using-ARDUINO
int Red1 = 13;
int Green1 = 12;
int Red2 = 8;
int Green2 = 6;
int Red3 = 3;
int Green3 = 2;
void setup()
{
  pinMode(Red1, OUTPUT);
  pinMode(Green1, OUTPUT);
  pinMode(Red2, OUTPUT);
  pinMode(Green2, OUTPUT);
  pinMode(Red3, OUTPUT);
  pinMode(Green3, OUTPUT);
}

void loop()
{
  digitalWrite(Red1, HIGH);
  digitalWrite(Red2, HIGH);
  digitalWrite(Red3, HIGH);
  delay(1000);
  
  digitalWrite(Red1, LOW);
  digitalWrite(Red2, LOW);
  digitalWrite(Red3, LOW);
  delay(500);
  
  digitalWrite(Green1, HIGH);
  digitalWrite(Green2, HIGH);
  digitalWrite(Green3, HIGH);
  delay(1000);
   
  digitalWrite(Green1, LOW);
  digitalWrite(Green2, LOW);
  digitalWrite(Green3, LOW);
  delay(500);
}
