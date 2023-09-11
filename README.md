# termux
-----------------

# Обновление Termux
```bash
pkg install git -y ; cd ~/ ; git clone https://github.com/linuxshef/termux.git ; cd termux ; ./update
```
--------------

Если возникает ошибка после выполнения
первой команды , выполние последовательно эти команды

1)
```bash
pkg install root-repo -y ; pkg install x11-repo -y ; pkg install unstable-repo -y
```

2)
```bash
pkg install git -y ; cd ~/ ; git clone https://github.com/linuxshef/termux.git ; cd termux ; ./update
```
--------------
# Установка Manjaro в Termux

```bash
pkg install -y wget proot pv pulseaudio git ; cd ~/ ; git clone https://github.com/linuxshef/termux.git ; cd termux ; ./manjaro_run
```

Автозапуск

```bash
cd ~/ ; git clone https://github.com/linuxshef/termux.git ; cd termux ; ./manjaro_up
```
---------------------

# SSH Termux

--------------

Для настройки SSH скопировать и вставить в терминал

```bash
pkg install openssh git -y ; cd ~/ ; git clone https://github.com/linuxshef/termux.git ; ./termuxssh
```
--------------
