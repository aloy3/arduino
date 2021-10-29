# arduino
arduino for LED


int LED = 3;

// RGB LED Pins
int RED = 8;
int BLUE = 9;
int GREEN = 10;

void setup() {
  pinMode(LED, OUTPUT);

  // RGB LED setup
  pinMode(RED, OUTPUT);
  pinMode(BLUE, OUTPUT);
  pinMode(GREEN, OUTPUT);
}

void loop() {
  digitalWrite(LED, HIGH);
  delay(2000);
  digitalWrite(LED, LOW);
  delay(1000);

  // Light RGB LED
  digitalWrite(RED, 255);
  delay(2000);

  digitalWrite(RED, 0);
  delay(1000);
  
  digitalWrite(BLUE, 255);
  delay(2000);

  digitalWrite(BLUE, 0);
  delay(1000);
  
  digitalWrite(GREEN, 255);
  delay(2000);

  digitalWrite(GREEN, 0);
  delay(1000);
}
