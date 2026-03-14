# 📱 @kobzar_shevchenko — Instagram

> Проект: «Якби Тарас Шевченко мав Instagram»

## Структура проекту

```
shevchenko_instagram/
├── server.js        ← Node.js сервер (Express)
├── package.json
├── .gitignore
└── public/
    └── index.html   ← Сторінка Instagram
```

---

## 🚀 Деплой на Render.com (покроково)

### 1. Завантажте проект на GitHub

1. Зайдіть на https://github.com → New repository
2. Назва: shevchenko-instagram
3. Завантажте всі файли (крім node_modules)

### 2. Деплой на Render

1. Зайдіть на https://render.com → New → Web Service
2. Підключіть GitHub репозиторій
3. Налаштування:
   - Name: shevchenko-instagram
   - Runtime: Node
   - Build Command: npm install
   - Start Command: npm start
   - Instance Type: Free
4. Натисніть Create Web Service

---

## Локальний запуск

npm install
npm start
# відкрийте http://localhost:3000
