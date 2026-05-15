
# Code

```cpp
#include <DHT.h>
#include <ESP8266WiFi.h>
#include <ThingSpeak.h>

#define DHTPIN D4
#define DHTTYPE DHT11

const char* ssid = "George";
const char* password = "12345678";

void setup(){
 Serial.begin(115200);
}
```
