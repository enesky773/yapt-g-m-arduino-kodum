# yapt-g-m-arduino-kodum
arduino led yakma programım
void setup() {
  pinMode(13, OUTPUT); // 13 numaralı pin çıkış olarak ayarlandı
}

void loop() {
  digitalWrite(13, HIGH); // LED'i yak
  delay(1000);            // 1 saniye bekle
  digitalWrite(13, LOW);  // LED'i söndür
  delay(1000);            // 1 saniye bekle
}

