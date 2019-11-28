# HC---SR04const int trigPin = 9;
const int echoPin = 10;
const int ledPin = 13;

long duration;
int distance;
int safetyDistance;




void setup() {
 pinMode (trigPin,OUTPUT);
 pinMode (echoPin, INPUT);
 pinMode (ledPin, OUTPUT);
 Serial.begin (9600);
}

void loop() {
 digitalWrite (trigPin, LOW);
 delayMicroseconds(2);


 digitalWrite(ledPin, HIGH);


else
  digitalWrite(ledPin, LOW);
}
