# 1-1 在TinkerCAD開一個新的Circuit, 加上一個外部的LED, 並且ON (亮) 0.1秒, OFF(滅) 0.1秒

## 電路
![image](https://user-images.githubusercontent.com/90953219/133882723-6069655b-eee3-480b-9653-b7aa4987d658.png)



## 程式

![image](https://user-images.githubusercontent.com/90953219/133882807-3402b11c-c189-4cde-99b1-d498f0c87f56.png)

````C

void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  // turn the LED on (HIGH is the voltage level)
  digitalWrite(LED_BUILTIN, HIGH);
  delay(100); // Wait for 100 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(LED_BUILTIN, LOW);
  delay(100); // Wait for 100 millisecond(s)
}
````
