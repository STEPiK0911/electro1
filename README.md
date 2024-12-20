# Выполнил Погребняк Степан Сиваселвамович, работа 1


#include <Arduino.h>

void setup() {
  // Настройка пинов как выходов
  pinMode(PA0, OUTPUT);
  pinMode(PA1, OUTPUT);
  pinMode(PA2, OUTPUT);
  pinMode(PA3, OUTPUT);
}

void loop() {
  for (int i = 0; i < 4; i++) {
    digitalWrite(PA0 + i, HIGH); // Включить светодиод
    delay(500);                  // Задержка 500 мс
    digitalWrite(PA0 + i, LOW);  // Выключить светодиод
  }
}







https://github.com/user-attachments/assets/e812e5c4-1308-40bd-9946-e0dbbb23884a

