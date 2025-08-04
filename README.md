# README.md

🔧 Что было сделано
Сборка и настройка postmarketOS

Инициализация pmbootstrap и выбор канала systemd-edge.

Установка окружения XFCE4.

Включение systemd.

Добавление дополнительных пакетов и локализации.

Исправление ошибок при сборке ядра (APKBUILD и checksum).

Экспорт и установка образа.

Установка recovery

Скачан и прошит TWRP 3.5.2 для P3110 через Odin.

Преобразование .img в .tar для прошивки через Odin с помощью Image2Tar.

Прошивка postmarketOS

Использован готовый образ 20250725-1048-postmarketOS-v25.06-xfce4-0.6.0-samsung-espresso7-android-recovery.zip.

Установка через TWRP (предварительно вайп system, data, cache).

Настройка сети и SSH

Включён SSH через systemd.

Исправлен порт в sshd_config.

Настроен firewall в nftables (правка 50_ssh.nft для открытия порта 22).

Проверка работы сервиса через systemctl status sshd.

Оптимизация

Выключены ненужные службы.

Добавлено логирование для диагностики (journalctl).

Настройка автостарта Wi-Fi.
