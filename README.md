#  НЕТОЛОГИЯ

### Дипломная работа профессии "Сетевой инженер"

- [Задание](#Задание)
- [Графическая схема](#Графическая-схема)
- [План сети](#План-сети)
- [Конфиги](#Конфиги)
- [Пояснительная записка](#Пояснительная-записка)
- [Тестирование](#Тестирование)
- [Файл проекта](#Файл-проекта)

---

### Задание

Задание можно посмотреть по [ссылке](https://github.com/netology-code/ntw-diplom/blob/main/README.md), в репозитории Нетологии.

---

### Графическая схема

Итоговая графическая схема, которая реализована, с планом сети:

<img src="source/layout.png" width="800">

---

### План сети

План сети в табличном виде:
- [Таблица подсетей](tables/subnets.md).
- [Сводная таблица по интерфейсам](tables/interfaces.md).

---

### Конфиги

Список конфигурационных файлов:
- [main_access_sw_01](configs/01-main_access_sw_01_startup-config) <sub> [(комманды)](commands/01-main_access_sw_01) </sub>.
- [main_access_sw_02](configs/02-main_access_sw_02_startup-config) <sub> [(комманды)](commands/02-main_access_sw_02) </sub>.
- [main_access_sw_03](configs/03-main_access_sw_03_startup-config) <sub> [(комманды)](commands/03-main_access_sw_03) </sub>.
- [main_core_sw_01](configs/04-main_core_sw_01_startup-config) <sub> [(комманды)](commands/04-main_core_sw_01) </sub>.
- [main_core_sw_02](configs/05-main_core_sw_02_startup-config) <sub> [(комманды)](commands/05-main_core_sw_02) </sub>.
- [main_voip_serv_01](configs/06-main_voip_serv_01_startup-config) <sub> [(комманды)](commands/06-main_voip_serv_01) </sub>.
- [main-asa-01](configs/07-main-asa-01_startup-config) <sub> [(комманды)](commands/07-main_asa_01) </sub>.
- [main-asa-02](configs/08-main-asa-02_startup-config) <sub> [(комманды)](commands/08-main_asa_02) </sub>.
- [main_border_01](configs/09-main_border_01_startup-config) <sub> [(комманды)](commands/09-main_border_01) </sub>.
- [main_border_02](configs/10-main_border_02_startup-config) <sub> [(комманды)](commands/10-main_border_02) </sub>.
- [branch1_border_01](configs/11-branch1_border_01_startup-config) <sub> [(комманды)](commands/11-branch1_border_01) </sub>.
- [branch1_access_sw_01](configs/12-branch1_access_sw_01_startup-config) <sub> [(комманды)](commands/12-branch1_access_sw_01) </sub>.
- [PROVIDER](configs/13-PROVIDER_startup-config) <sub> [(комманды)](commands/13-PROVIDER) </sub>.

Также конфигурация через GUI:
- [main_infr_serv_01_DHCP](configs_gui/01-main_infr_serv_01_DHCP.png).
- [main_infr_serv_01_DNS](configs_gui/02-main_infr_serv_01_DNS.png).
- [main_infr_serv_01_AAA](configs_gui/03-main_infr_serv_01_AAA.png).
- [main_infr_serv_01_SYSLOG](configs_gui/04-main_infr_serv_01_SYSLOG.png).
- [main_infr_serv_01_NTP](configs_gui/05-main_infr_serv_01_NTP.png).
- [main_wlc_01_MAIN_WIFI](configs_gui/06-main_wlc_01_MAIN_WIFI.png).
- [main_wlc_01_BRANCH1_WIFI](configs_gui/07-main_wlc_01_BRANCH1_WIFI.png).
- [main_wlc_01_MAIN_AP](configs_gui/08-main_wlc_01_MAIN_AP.png).
- [main_wlc_01_BRANCH1_AP](configs_gui/09-main_wlc_01_BRANCH1_AP.png).
- [PUBLIC_DNS](configs_gui/10_PUBLIC_DNS.png).

---

### Пояснительная записка

[Пояснение](https://github.com/mkAdmin11/crpnt-final/tree/main/explanation#пояснительная-записка) к выполненой работе.

---

### Тестирование

[Тестирование](https://github.com/mkAdmin11/crpnt-final/tree/main/testing#тестирование) выполнено по [заданию](https://github.com/netology-code/ntw-diplom/blob/main/README.md#тестирование).

---

### Файл проекта

[Ссылка](cpt) на pkt-файл.
