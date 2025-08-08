# 👋 Привет, меня зовут Anniversary

📡 Я инженер-энтузиаст с интересом к системному программированию, Embedded Linux и построению инфраструктуры мониторинга в условиях ограниченных ресурсов. Работаю с ARM-устройствами, контейнерами и низкоуровневыми Linux-инструментами.

---

## 🚀 О проектах

### 🧠 Инфраструктура мониторинга на базе Docker

Создана масштабируемая система мониторинга и логирования с использованием:

- 🧩 **NGINX** + `stub_status`
- 📦 **Prometheus** + `nginx-prometheus-exporter` + **Node Exporter**
- 📊 **Grafana** с автопровиженингом дашбордов
- 📄 **Loki** + **Promtail** для логирования
- 🐳 Всё разворачивается через `docker-compose` с томами и изоляцией в сети `monitoring`

🔍 *Используется для мониторинга HTTP-запросов, системных ресурсов и анализа логов в реальном времени.*

---

### 📱 ARM-устройства и кастомные Linux-сборки

#### 📌 **postmarketOS + XFCE4 на Samsung Galaxy Tab 2 (GT-P3110)**

- Собрал и установил кастомный образ `postmarketOS` с XFCE4 и `Open-rc`
- Настроил кастомный **TWRP**, ADB sideload и SSH-доступ через `nftables`
- Запускал **Docker и docker-compose** на ARMv7

#### 📌 **Linux ARMEL-дистрибутив на LG P500 (ARMv6)**

- ⚙️ Установлен **TWRP** для загрузки альтернативных систем.
- 📲 Обновлён Android до **CyanogenMod 9 (4.0.4)** для поддержки chroot.
- 🐧 Запуск и тестирование **Debian ARMEL** и **Alpine Linux** на архитектуре ARMv6.
- 📦 Установка **BusyBox**, распаковка и запуск `rootfs` в chroot.
- 🧠 Оптимизация rootfs для работы в условиях **≤512 MB RAM**, **≤512 MB ROM**.
- 🛠️ Использование только низкоуровневых инструментов без Docker и systemd.

- 🔍 В планах разработки: инфраструктура на базе **Nginx**, **collectd** и **RRDTool**.

---

## 🧰 Навыки и технологии

### 💻 DevOps и мониторинг

![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white&style=flat)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white&style=flat)
![Loki](https://img.shields.io/badge/-Loki-0E1117?logo=grafana&style=flat)
![Node Exporter](https://img.shields.io/badge/-Node%20Exporter-000000?style=flat&logo=prometheus)

### 📦 Embedded и низкоуровневый Linux

- ARMv6 / ARMv7
- `BusyBox`, `chroot`, `nftables`, `OpenSSH`
- `TWRP`, `CWM`, `pmbootstrap`

### 🧪 Языки и инструменты

![Bash](https://img.shields.io/badge/-Bash-121011?logo=gnu-bash&style=flat)
![Markdown](https://img.shields.io/badge/-Markdown-000000?logo=markdown&style=flat)
![YAML](https://img.shields.io/badge/-YAML-CB171E?logo=yaml&style=flat)
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white&style=flat)
![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2b%2b&logoColor=white&style=flat)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat)

---

## 📈 GitHub Stats

![t0buleu's GitHub stats](https://github-readme-stats.vercel.app/api?username=t0buleu&show_icons=true&theme=dark&hide_title=true)

---

## 📫 Контакты

- 🔗 Email: [i@t0buleu.ru](mailto:i@t0buleu.ru)
- 💡 На стыке креатива и технологий — люблю не просто изучать, а использовать технику по максимому

---

