# DC-Motor-with-h-bridge
// C++ code
//
void setup()
{
  pinMode(11, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(11, HIGH);
  digitalWrite(12, LOW);
  delay(5000); // Wait for 5000 millisecond(s)

  digitalWrite(11, LOW);
  digitalWrite(12, HIGH);
}
تشغيل الـ DC  تدور عكس عقارب الساعة 
تتوقف لمدة 5 ثواني
تدور عقارب الساعة في اتجاه عقارب الساعة 
