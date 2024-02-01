// Blinks an LED attached to a MCP23XXX pin.

// ok to include only the one needed
// both included here to make things simple for example
//#include <Adafruit_MCP23X08.h>
#include <Adafruit_MCP23X17.h>

#define OUTPUT1 7
#define OUTPUT2 6
#define OUTPUT3 5
#define OUTPUT4 4
#define OUTPUT5 8
#define OUTPUT6 9
#define OUTPUT7 10
#define OUTPUT8 11



// uncomment appropriate line
//Adafruit_MCP23X08 mcp;
Adafruit_MCP23X17 mcp;

void setup() {
  Serial.begin(115200);
  //while (!Serial);
  Serial.println("NORVO Expansions Test");

  // uncomment appropriate mcp.begin
  Wire.begin (16, 17);   
  if (!mcp.begin_I2C(0x27)) {
    Serial.println("Error.");
    while (1);
  }

  // configure pin for output
  mcp.pinMode(OUTPUT1, OUTPUT);
  mcp.pinMode(OUTPUT2, OUTPUT);
  mcp.pinMode(OUTPUT3, OUTPUT);
  mcp.pinMode(OUTPUT4, OUTPUT);
  mcp.pinMode(OUTPUT5, OUTPUT);
  mcp.pinMode(OUTPUT6, OUTPUT);
  mcp.pinMode(OUTPUT7, OUTPUT);
  mcp.pinMode(OUTPUT8, OUTPUT);

  Serial.println("Looping...");
}

void loop() {
  mcp.digitalWrite(OUTPUT1, HIGH);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, HIGH);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, HIGH);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, HIGH);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, HIGH);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, HIGH);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, HIGH);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, HIGH);
  delay(500);
  mcp.digitalWrite(OUTPUT1, LOW);
  mcp.digitalWrite(OUTPUT2, LOW);
  mcp.digitalWrite(OUTPUT3, LOW);
  mcp.digitalWrite(OUTPUT4, LOW);
  mcp.digitalWrite(OUTPUT5, LOW);
  mcp.digitalWrite(OUTPUT6, LOW);
  mcp.digitalWrite(OUTPUT7, LOW);
  mcp.digitalWrite(OUTPUT8, LOW);
  delay(500);
  Serial.println("Looping...");
}
