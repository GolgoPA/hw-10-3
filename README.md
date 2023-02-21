# 10-3-hw Домашнее задание к занятию 10.3 «Pacemaker»

---

### Задание 1

Опишите основные функции и назначение Pacemaker.

*Приведите ответ в свободной форме.*

- Обнаружение и восстановление сбоев на уровне узлов и
сервисов
- Независимость от подсистемы хранения
- Независимость от типов ресурсов
- Поддержка Shoot-The-Other-Node-In-The-Head
- Поддержка кластеров любого размера
- Поддержка и кворумных и ресурсозависимых кластеров
- Поддержка практически любой избыточной конфигурации
- Автоматическая репликация конфига на все узлы кластера
- Возможность задания порядка запуска ресурсов, а также их
совместимости на одном узле
- Поддержка расширенных типов ресурсов
- Единый кластерный шелл (crm), унифицированный,
скриптующийся

---

### Задание 2

Опишите основные функции и назначение Corosync.

*Приведите ответ в свободной форме.*

- Отслеживание состояния приложений
- Оповещение приложений о смене активной ноды кластера
- Отправка одинаковых сообщений процессам на всех узлах
кластера
- предоставление доступа к базе данных с конфигурацией и
статистикой, а также отправка уведомлений об ее изменениях

---

### Задание 3

Соберите модель, состоящую из двух виртуальных машин. Установите Pacemaker, Corosync, Pcs. Настройте HA кластер.

*Пришлите скриншот рабочей конфигурации и состояния сервиса для каждого нода.*

---

### Задания со звёздочкой*
Эти задания дополнительные. Выполнять их не обязательно. Это не повлияет на зачёт. Вы можете их выполнить, если хотите глубже разобраться в материале.
 
---

### Задание 4

Установите и настройте DRBD-сервис для настроенного кластера.

*Пришлите скриншот рабочей конфигурации и состояние сервиса для каждого нода.*

