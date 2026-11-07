# 👋 Привет, я Никита — DevOps-инженер

Автоматизирую рутину и строю предсказуемую инфраструктуру. 
Более 3 лет опыта в IT: прошел путь от системного администрирования и разработки до DevOps-инженерии. Фокус на автоматизации развертывания, сборке пакетов и наблюдаемости.

## 🛠 Основной стек

**ОС и виртуализация:**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A8B8CC?style=for-the-badge&logo=debian&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Astra Linux](https://img.shields.io/badge/Astra_Linux-0054A6?style=for-the-badge&logo=linux&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)

**Автоматизация, CI/CD и сборка пакетов:**  
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Ansible Vault](https://img.shields.io/badge/Ansible_Vault-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Контейнеризация и сети:**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefik-proxy&logoColor=white)

**Мониторинг и логирование:**  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## 🚀 Текущие задачи и достижения
- 📦 **Сборка пакетов и развертывание:** Разработка `preseed` для автоустановки Astra Linux. Упаковка ПО, БД и индивидуальных настроек заказчика в `.deb`-пакеты. Создание метапакетов (в том числе для средств разработки). Массовая установка и настройка через Ansible.
- 🔄 **CI/CD для Qt/C++:** Построение пайплайна со статическим анализом (`cppcheck`), управлением зависимостями, сборкой разных версий, релизом в GitLab Package Registry и уведомлениями о падениях.
- 🌐 **Сети и безопасность:** Проектирование сетевой архитектуры проектов. Настройка коммутаторов для сегментации трафика и изоляции устройств с одинаковыми IP-адресами (ARP inspection, ACL/ARP ACL). Фильтрация трафика на уровне ОС (`iptables`).
- 🏗 **Инфраструктура:** Управление ВМ на Proxmox, использование GitLab Docker Registry для собственных образов.
- 🔐 **Безопасность (доступы):** Ansible Vault для секретов в репозитории, защищённые переменные (Protected Variables) в GitLab CI/CD.
- 🐳 **Контейнеризация:** Docker и Docker Compose для внутренних задач, Traefik в качестве обратного прокси-сервера.
- 📊 **Наблюдаемость:** Prometheus + Grafana для метрик и визуализации.
- 📝 **Документация:** Ведение базы знаний, сетевых схем и таблиц адресации. Визуализация архитектуры через draw.io и Mermaid.

## 🎯 Фокус развития (ближайшие 6–12 мес.)
- 📦 **Собственный apt-репозиторий:** Развертывание и поддержка репозитория для дистрибуции `.deb`-пакетов нашего ПО.
- 🚀 **Оптимизация доставки:** Настройка rsync-сервера для быстрой передачи больших файлов на клиентские машины через Ansible-роли.
- ☸️ **Kubernetes:** Изучение архитектуры и переход от Docker Compose к K8s в домашних проектах.
- 🏗 **Terraform:** Декларативное развёртывание инфраструктуры (изучение плагина для Proxmox).
- 📊 **Наблюдаемость:** Внедрение Grafana Loki для централизованного сбора логов.

## 📫 Контакты
- 📧 Email: [nikita.mikhailov.it@ya.ru](mailto:nikita.mikhailov.it@ya.ru)
- 💼 **Открыт к предложениям:** DevOps-инженер (Удаленно, РФ)
