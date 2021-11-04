# Нативный священный Биборан
Священный Биборан с гуем на GTK-3 для отпугивания маслачей. Удобно читать не отрываясь от работы.

![biboran](https://imgur.com/bqFhW3t.jpg)

## Собрать
Поставьте GTK-3 для вашей платформы. Например так:
```bash
$ sudo apt-get install gtk+3.0
```
Теперь осталось собрать. Для ленивых есть compile.sh:
```bash
$ chmod +x compile.sh && ./compile.sh
```
Или так:
```bash
$ gcc biboran.c -O3 -o biboran `pkg-config --cflags --libs gtk+-3.0`
```

