# q5
#include "wifi.h"
#inculde "ESPA sycnWebServer.h"
#include "DHTesp.h"
#include "softwareSerial.h"
#include "MHZ19.h"
#define Rx_PIN 33
#define Tx_PIN 32
int dhtPin =4;
DHTesp dht;
MHZ19 myMHZ19;
softwareSerial myserial(Rx_PIN,Tx_PIN);
AsyncWebServer Server(80);
Const char* ssid="network name";
Const char* ssid="password";
Serial.begin(115200);
wifi.begin(ssid,password);
server.on("/co2",HTTP_GET,[](Asyncweb server Request* request))};
