# 1-2 在TinkerCAD開一個新的Circuit, 分別使甪R, G, B三種顏色的LED, ON (亮) 0.5秒, OFF(滅) 0.5秒


## 電路

![image](https://user-images.githubusercontent.com/90953219/133883256-324dfc5a-1d51-4bca-b521-a4a83a47e366.png)

## 程式
````C
void setup()
{
  pinMode(13, OUTPUT); // RED
  pinMode(11, OUTPUT); // YELLOW
  pinMode(9, OUTPUT); // GREEN
  
}

void loop()
{
  // turn the LED on (HIGH is the voltage level)
  digitalWrite(13, HIGH);
  digitalWrite(11, HIGH);
  digitalWrite(9, HIGH);
  
  delay(500); // Wait for 1000 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(13, LOW);
  digitalWrite(11, LOW);
  digitalWrite(9, LOW);
  
  delay(500); // Wait for 1000 millisecond(s)
}
````
