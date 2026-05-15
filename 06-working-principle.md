
# 5. Working Principle

## DHT Sensor
- Single-wire communication
- 40-bit data

## ESP8266
- Reads sensor
- Sends data

## ThingSpeak
- Stores data
- Displays graphs

## Control
```cpp
BLYNK_WRITE(V10){
 int state = param.asInt();
 digitalWrite(RELAY_PIN, state ? HIGH : LOW);
}
