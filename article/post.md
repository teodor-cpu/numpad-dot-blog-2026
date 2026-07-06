# Точка вместо запетая при натискане на Del / Decimal бутона от NumPad

Ако при българска клавиатура бутонът Del / Decimal от NumPad пише `,` вместо `.`, най-лесното решение през 2026 г. е малък registry remap.

Това решение:

- не иска допълнителна програма
- не пуска скрипт при startup
- работи на системно ниво

Важно: промяната е глобална за всички клавиатурни подредби и изисква рестарт на Windows.

## Изтегляне

- Включване: [numpad-decimal-dot-enable.reg](https://github.com/teodor-cpu/numpad-dot-blog-2026/releases/download/v1.0.0/numpad-decimal-dot-enable.reg)
- Връщане назад: [numpad-decimal-dot-disable.reg](https://github.com/teodor-cpu/numpad-dot-blog-2026/releases/download/v1.0.0/numpad-decimal-dot-disable.reg)
- Целият пакет: [numpad-dot-blog-2026.zip](https://github.com/teodor-cpu/numpad-dot-blog-2026/releases/download/v1.0.0/numpad-dot-blog-2026.zip)

## Как се прави

1. Свалете [numpad-decimal-dot-enable.reg](https://github.com/teodor-cpu/numpad-dot-blog-2026/releases/download/v1.0.0/numpad-decimal-dot-enable.reg).
2. Стартирайте файла с двоен клик.
3. Потвърдете предупреждението на Windows.
4. Рестартирайте компютъра.

След рестарта бутонът Decimal / Del от NumPad ще пише точка.

## Ако искате да върнете старото поведение

1. Свалете [numpad-decimal-dot-disable.reg](https://github.com/teodor-cpu/numpad-dot-blog-2026/releases/download/v1.0.0/numpad-decimal-dot-disable.reg).
2. Стартирайте файла.
3. Рестартирайте Windows.

## Важно уточнение

Смяната на decimal separator в Regional settings не решава надеждно проблема при стандартните български Windows keyboard layouts. Там поведението на NumPad Decimal обикновено идва от самата клавиатурна подредба.

Ако искате промяната да важи само за една конкретна българска подредба, тогава трябва custom keyboard layout. За повечето хора обаче `.reg` вариантът е по-простият и практичен избор.
