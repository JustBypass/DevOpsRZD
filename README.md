# Развертывание Prometheus и Grafana с использованием Ansible и Docker

## Задача
В данном задании требуется развернуть Prometheus на хосте с помощью простого Ansible плейбука без использования ролей. Также необходимо развернуть Grafana в Docker контейнере и настроить сохранение нарисованных дашбордов для обеспечения stateless работы. 

## Шаги выполнения
1. **Развертывание Prometheus с помощью Ansible:**
   - Написать простой плейбук для установки и настройки Prometheus.

2. **Развернуть Grafana в Docker контейнере:**
   - Создать Docker контейнер для Grafana.
   - Настроить сохранение данных дашбордов для обеспечения stateless работы.

3. **Создать дашборд в Grafana:**
   - Создать дашборд, мониторящий состояние метрик Docker контейнеров.

4. **Сохранение авторизационных данных:**
   - Обеспечить сохранение авторизационных данных для Grafana, чтобы обеспечить stateless работу.

## Дополнительная информация
- Для развертывания Prometheus и Grafana можно использовать Docker, Ansible и другие инструменты автоматизации.
- При создании дашборда в Grafana учтите требования по мониторингу состояния метрик Docker контейнеров.
