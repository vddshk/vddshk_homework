# 📦 Flask-приложение в Docker  

Это простое веб-приложение на Flask, которое работает внутри Docker-контейнера и отвечает "Hello, Docker!" на запросы.  

## 🚀 Запуск проекта  

### **1. Установка Docker**  
Перед началом убедитесь, что у вас установлен **Docker**. Если нет, скачайте и установите его с [официального сайта](https://www.docker.com/get-started/).  

### **2. Клонирование репозитория**  
```sh
git clone [https://github.com/vddshk/vddshk_homework.git]
cd docker-flask-app
```

### **3. Сборка Docker-образа**  
```sh
docker build -t my-flask-app .
```

### **4. Запуск контейнера**  
```sh
docker run -p 5000:5000 my-flask-app
```

### **5. Проверка работы**  
Откройте браузер и перейдите по адресу:  
[http://localhost:5000](http://localhost:5000)  

Или выполните команду в терминале:  
```sh
curl http://localhost:5000
```

## 🛠 Дополнительные команды  

### **Остановка контейнера**  
Найдите запущенный контейнер:  
```sh
docker ps
```
Остановите его, используя `CONTAINER_ID`:  
```sh
docker stop CONTAINER_ID
```

### **Запуск в фоновом режиме (-d)**  
```sh
docker run -d -p 5000:5000 my-flask-app
```

## 🐳 Полезные ссылки  
- [Документация Docker](https://docs.docker.com/)  
- [Flask Docs](https://flask.palletsprojects.com/)  

---  
Если есть вопросы или проблемы — пишите! 🚀  
