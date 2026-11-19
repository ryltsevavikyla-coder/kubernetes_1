# Домашнее задание к занятию «Запуск приложений в K8S»
# Домашнее задание: Запуск приложений в K8S

## Задание 1. Deployment с nginx + multitool

### Манифесты
- [deployment-nginx-multitool.yaml](deployment-nginx-multitool.yaml)
- [service-nginx-multitool.yaml](service-nginx-multitool.yaml)



### Скриншоты

**Поды до масштабирования:**

![pods-before](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20132009.png?raw=true)

**Поды после масштабирования:**

![pods-after](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20132156.png?raw=true)

**Service:**

![service](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20133022.png?raw=true)

**Проверка через curl:**

![curl](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20132704.png?raw=true)

---

## Задание 2. Init-контейнер

### Манифесты
- [deployment-nginx-init.yaml](deployment-nginx-init.yaml)
- [service-nginx-init.yaml](service-nginx-init.yaml)



### Скриншоты

**До создания Service (Init:0/1):**

![init-before](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20133536.png?raw=true)

**После создания Service (Running):**

![init-after](https://github.com/ryltsevavikyla-coder/kubernetes_1/blob/main/Screenshot%202026-11-19%20133926.png?raw=true)
