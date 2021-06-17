<a href="https://github.com/riclolsen/json-scada/">
    <img src="https://github.com/riclolsen/json-scada/raw/master/src/htdocs/images/json-scada.svg" alt="JSON:SCADA Logo" title="JSON:SCADA" align="right" height="60" />
</a>

{json:scada}
============

Портативна і масштабуюча платформа SCADA/IoT, згуртована навкруги сервера баз даних MongoDB.

![](https://img.shields.io/badge/node-%3E%3D14-green "Node.js >= 14")
![](https://img.shields.io/badge/golang-%3E%3D1.14-green "Go >= 1.14")
![](https://img.shields.io/badge/dotnet-%3E%3D5.0-green "Dotnet >=5.0")

![](https://img.shields.io/badge/mongodb-%3E%3D4.2-green "MongoDB >= 4.2")
![](https://img.shields.io/badge/postgresql-12-green "PostgreSQL 12")
![](https://img.shields.io/badge/timescaledb-2.0-green "TimescaleDB 2.0")
![](https://img.shields.io/badge/grafana-%3E%3D7-green "Grafana >= 7")

![](https://img.shields.io/badge/linux-x86--64-green "Linux x86-64")
![](https://img.shields.io/badge/linux-ARM-green "Linux ARM")
![](https://img.shields.io/badge/windows-x86--64-green "Windows x86-64")
![](https://img.shields.io/badge/macosx-x86--64-green "Mac OSX x86-64")
![](https://img.shields.io/badge/macosx-ARM--M1-yellow "Mac ARM M1 x86-64")

![](https://img.shields.io/badge/IEC60870--5--104-green "IEC60870-5-104")
![](https://img.shields.io/badge/IEC60870--5--101-green "IEC60870-5-101")
![](https://img.shields.io/badge/DNP3-green "DNP3")
![](https://img.shields.io/badge/MQTT-green "MQTT")
![](https://img.shields.io/badge/Sparkplug--B-green "Sparkplug B")
![](https://img.shields.io/badge/OPC--UA-yellow "OPC-UA")
![](https://img.shields.io/badge/CIP.Ethernet/IP-yellow "CIP Ethernet/IP")

![](https://img.shields.io/badge/license-GPL-green "License GPL")
![](https://img.shields.io/badge/contributors-welcome-green "Contributors Welcome")

## Опис місії

Надати просту у використанні, повнофункціональну, масштабовану та портативну платформу SCADA/IIoT-I4.0, побудовану за рахунок використання основних ІТ-інструментів з відкритим кодом.

## Screenshots

![screenshots](https://github.com/riclolsen/json-scada/raw/master/docs/screenshots/anim-screenshots.gif "{json:scada} Screenshots")

## Основні особливості та характеристики

* Стандартні додатки ІТ, згуртовані навкруги SCADA/IoT (MongoDB, PostgreSQL/TimescaleDB, Node.js, C #, Golang, Grafana тощо).
* MongoDB як основна база даних реального часу, рівень стійкості, сховище конфігурацій, гістограм SOE.
* Обробка асинхронних даних у реальному часі на основі подій за допомогою MongoDB Change Streams.
* Переносимість та модульна сумісність у Linux, Windows, Mac OSX, x86/64, ARM.
* Інсталятор Windows доступний у [розділі випусків] (<https://github.com/riclolsen/json-scada/releases/tag/V0.10-alpha>).
* Необмежена кількість тегів, серверів та користувачів.
* Горизонтальна масштабованість, від одного комп'ютера до великих кластерів (шардинг MongoDB), контейнерів Docker, віртуальних машин, Kubernetes, хмарних або гібридних розгортань.
* Модульна розподілена архітектура. Легкі надлишкові вузли збору даних можуть надійно підключатися через TLS до сервера баз даних. Наприклад Raspberry PI може бути вузлом збору даних.
* Розширюваність основної моделі даних (MongoDB: NoSQL/schema-less).
* Веб-інтерфейс HTML5. UTF-8/I18N. Мобільний доступ. Веб-управління конфігурацією.
* Рольовий контроль доступу (RBAC).
* Різні високоякісні драйвери протоколів.
* Інтеграція з брокерами MQTT (сумісність із Sparkplug B).
* Оновлення конфігурації поточної точки.
* Редактор синоптичних дисплеїв SVG на основі Inkscape.
* Історик PostgreSQL/TimescaleDB інтегрований з Grafana для зручного створення інформаційних панелей.
* Проста розробка спеціальних програм із сучасними стеками, такими як MEAN/MERN тощо. Широке використання JSON знизу вгору.
* Використовуйте величезну екосистему інструментів спільноти MongoDB/PostgreSQL, послуг, тощо.

## Випадки використання

* Електро/Нафто/Газо/Комунальних організаціях, локальне устаткування HMI.
* Виробництво на невеликих, локальних HMI.
* Шлюз протоколу SCADA.
* Глобальна система SCADA Control Center.
* Історичні данні SCADA/IoT. Інтеграція MS Power BI.
* Інтранет/Інтернет HTTPS шлюз - сервер візуалізації.
* Багаторівневий системний інтегратор (SCADA/IoT/ERP/MES/PLC).
* Інтеграція/централізація систем SCADA глобального рівня.
* Розширювана платформа розвитку для збору та обробки даних.

* Концентратор даних для обробки BigData/ML.

## Архітектура

![architecture](docs/ua_JSON-SCADA_ARCHITECTURE.png "{json:scada} Architecture")

## Документація

* [Install Guide](https://github.com/riclolsen/json-scada/blob/master/docs/install.md)
* [Windows installer](https://github.com/riclolsen/json-scada/releases/tag/V0.9-alpha)
* [Docker Demo](https://github.com/riclolsen/json-scada/blob/master/demo-docker/README.md)
* [Schema Documentation](https://github.com/riclolsen/json-scada/blob/master/docs/schema.md)
* [Config File](https://github.com/riclolsen/json-scada/blob/master/conf/README.md)
* [SVG Synoptic Display Editor](https://github.com/riclolsen/json-scada/blob/master/src/svg-display-editor/README.md)
* [IEC60870-5-104 Server Driver](https://github.com/riclolsen/json-scada/blob/master/src/lib60870.netcore/iec104server/README.md)
* [IEC60870-5-104 Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/lib60870.netcore/iec104client/README.md)
* [IEC60870-5-101 Server Driver](https://github.com/riclolsen/json-scada/blob/master/src/lib60870.netcore/iec101server/README.md)
* [IEC60870-5-101 Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/lib60870.netcore/iec101client/README.md)
* [DNP3 Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/dnp3/Dnp3Client/README.md)
* [Telegraf Listener Driver](https://github.com/riclolsen/json-scada/blob/master/src/telegraf-listener/README.md)
* [MQTT Sparkplug-B Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/mqtt-sparkplug/README.md)
* [OPC-UA Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/OPC-UA-Client/README.md)
* [CIP Ethernet/IP PLCTags Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/libplctag/PLCTagsClient/README.md)
* [I104M Client Driver](https://github.com/riclolsen/json-scada/blob/master/src/i104m/README.md)
* [Calculations](https://github.com/riclolsen/json-scada/blob/master/src/calculations/README.md)
* [Change Stream Data Processor](https://github.com/riclolsen/json-scada/blob/master/src/cs_data_processor/README.md)
* [Custom Data Processor](https://github.com/riclolsen/json-scada/blob/master/src/cs_custom_processor/README.md)
* [Realtime Data Server](https://github.com/riclolsen/json-scada/blob/master/src/server_realtime/README.md)
* [OSHMI2JSON Tool](https://github.com/riclolsen/json-scada/blob/master/src/oshmi2json/README.md)
* [Report Generators](https://github.com/riclolsen/json-scada/blob/master/docs/report_generators.md)

## Протоколи план дій

- [x] IEC 60870-5-104 Server TCP
- [ ] IEC 60870-5-104 Server TLS
- [x] IEC 60870-5-104 Client TCP/TLS
- [x] IEC 60870-5-101 Server (Serial, TCP)
- [x] IEC 60870-5-101 Client (Serial, TCP)
- [ ] IEC 60870-5-103 Client
- [x] DNP3 Client (TCP, UDP, TLS, Serial)
- [ ] DNP3 Server (TCP, UDP, TLS, Serial)
- [x] MQTT/Sparkplug-B Client
- [x] I104M (adapter for some OSHMI drivers)
- [x] ICCP Client (via I104M)
- [ ] Secure ICCP Client
- [x] Telegraf Client (OPC-UA, MQTT, MODBUS, SNMP, ...)
- [x] OPC UA Client (experimental)
- [ ] OPC UA Server
- [ ] OPC DA Client
- [ ] OPC DA Server
- [ ] Modbus Client
- [ ] IEC 61850 MMS Client
- [ ] IEC 61850 GOOSE Client
- [x] CIP Ethernet/IP (libplctag, experimental)
- [ ] Siemens S7
- [ ] BACNET
- [ ] OPC UA Historical Data Server

## Особливості план дій

- [x] Web-based Viewers
- [x] Web-based Configuration Manager
- [x] User auth/Role-based Access Control (RBAC)
- [x] Inkscape-based SVG Synoptic Editor
- [x] Compiled Calculations Engine
- [x] Customizable Change-Stream Processor (for user implemented scripts)
- [ ] Low-latency/Interpreted Calculations Engine
- [x] Basic Alarms Processor
- [ ] Advanced Alarms Processor 
- [x] PostgreSQL/TimescaleDB Historian
- [x] Grafana Integration 
- [x] Grafana Alerting Integration (w/ Events Viewer)
- [x] Windows Installer
- [x] Online Demo
- [x] Docker Demo (docker-compose.yaml scripts)
- [x] Dedicated Docker Containers
- [ ] Linux Image / VM
- [x] Supervisor (Linux process manager) examples
- [ ] InfluxDB Integration
- [x] Telegraf Integration
- [ ] Kafka Integration
- [x] PowerBI Integration (via PostgreSQL connector)
- [ ] PowerBI Direct Integration
- [ ] NodeRed Integration
- [x] Metabase Integration (via PostgreSQL connector)
- [ ] Alerta Integration (https://alerta.io/)
- [ ] PLC4X Integration (https://plc4x.apache.org/)
- [ ] Managed Cloud Service

## Демонстрація Онлайн (симуляція підстанцій)

* http://vmi233205.contaboserver.net:8080/

Ця демонстрація забезпечує загальнодоступний порт сервера IEC 60870-5-104 на IP-адресу 207.180.242.96:2404 (загальна адреса = 1) для тестування.

Демонстраційні дані публікуються як звичайні теми MQTT для публічного брокера mqtt://test.mosquitto.org:1883 (близько 8600 тем у ACME_Utility/#).

Дані також публікуються як Sparkplug-B на mqtt://test.mosquitto.org:1883 (близько 4300 метрик пристроїв у spBv1.0/Sparkplug B Devices/+/JSON-SCADA Server/#). Дані/походження стискаються за допомогою бібліотеки Eclipse Tahu Javascript.

## Developer Contact

* https://www.linkedin.com/in/ricardo-olsen/
