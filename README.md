# numpad-dot-blog-2026

Готов пакет за блог публикация и download файлове за промяна на NumPad Decimal от `,` към `.` под Windows.

## Съдържание

- `article/post.md` - пълна markdown версия на статията
- `article/blogger-post.html` - HTML версия, удобна за директно paste-ване в Blogger
- `downloads/numpad-decimal-dot-enable.reg` - включва промяната
- `downloads/numpad-decimal-dot-disable.reg` - връща стандартното поведение

## Какво прави

Промяната remap-ва клавиша NumPad Decimal / Del на системно ниво чрез `Scancode Map` в Windows registry.

Важно:

- нужен е restart на Windows
- промяната е глобална за всички клавиатурни подредби
- не изисква фонова програма или скрипт

## Препоръчано хостване

За безплатно и дългосрочно хостване:

1. качи repo-то в GitHub
2. създай Release
3. прикачи `.reg` файловете или zip архив като Release assets
4. сложи линка към Release-а в блог публикацията
