# MaxProff

🚀 **MaxProff** — це сучасний лендінг-проект, що використовує **Gulp** для автоматизації задач, **SCSS** для стилізації та **Vanilla JavaScript** для інтерактиву.

---

## 🧩 Технології

- **HTML5**  
- **SCSS (Sass)**  
- **JavaScript (ES6+)**  
- **Gulp** — для збірки, обробки стилів, скриптів, HTML та запуску локального сервера  

---

## 📁 Структура проекту

```
MaxProff/
│
├── dist/              # Фінальна збірка (автоматично генерується)
├── node_modules/      # Зовнішні залежності (ігноруються в Git)
├── src/               # Вихідні файли
│   ├── assets/        # Зображення, шрифти, іконки
│   ├── js/            # JavaScript-файли
│   ├── sass/          # SCSS стилі
│   │   ├── base/      # Змінні, міксини, reset
│   │   ├── blocks/    # Стилі окремих блоків
│   │   ├── libs/      # Сторонні бібліотеки
│   │   └── style.scss # Головний SCSS-файл
│   └── index.html     # Головна HTML-сторінка
│
├── .gitignore         # Файли та папки, що не відслідковуються Git
├── gulpfile.js        # Налаштування Gulp
├── package.json       # Залежності та скрипти npm
└── package-lock.json  # Фіксація версій залежностей
```

---

## ⚙️ Встановлення та запуск

1. **Клонуй репозиторій**:
   ```bash
   git clone https://github.com/garroshe/MaxProff.git
   cd MaxProff
   ```

2. **Встанови залежності**:
   ```bash
   npm install
   ```

3. **Запусти локальний сервер з live reload**:
   ```bash
   npm run dev
   ```

   Це запустить Gulp-сервер, автоматично скомпілює SCSS, перенесе скрипти та HTML в `dist/`, і відкриє сторінку в браузері.

---

## 📦 Основні Gulp-задачі

- `styles` — компіляція та мініфікація SCSS
- `scripts` — копіювання JS
- `html` — мінімізація HTML
- `images` та `icons` — копіювання зображень та іконок
- `watch` — відстеження змін у файлах
- `server` — запуск локального сервера
- `default` — запуск всього одразу

---

## 💡 Автор

**Garroshe**  
[github.com/garroshe](https://github.com/garroshe)

---
