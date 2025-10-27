# Инструкция по загрузке на GitHub

## ✅ Что уже сделано:
1. ✅ Исправлен UFC 5 - добавлено изображение
2. ✅ Улучшен слайдер - добавлены красивые эффекты
3. ✅ Создан .gitignore
4. ✅ Сделан первый коммит

## 🚀 Как загрузить на GitHub:

### Шаг 1: Создайте репозиторий на GitHub
1. Откройте https://github.com
2. Нажмите "+" (правый верхний угол)
3. Выберите "New repository"
4. Название: `gamesfast-store` (или любое другое)
5. НЕ ставьте галочки (README, .gitignore, license)
6. Нажмите "Create repository"

### Шаг 2: Загрузите код

Выполните эти команды в терминале (замените YOUR_USERNAME на ваш GitHub username):

```bash
cd "/Users/prizrak/кбип 4 курс/Новая папка"

# Добавьте удаленный репозиторий
git remote add origin https://github.com/YOUR_USERNAME/gamesfast-store.git

# Переименуйте ветку в main (стандарт GitHub)
git branch -M main

# Загрузите код
git push -u origin main
```

### Альтернативный способ через GitHub Desktop:
1. Скачайте GitHub Desktop: https://desktop.github.com
2. Откройте приложение
3. File → Add Local Repository
4. Выберите папку проекта
5. Нажмите "Publish repository"

## 🌐 После загрузки:
GitHub автоматически создаст URL: `https://github.com/YOUR_USERNAME/gamesfast-store`

## 📝 Как обновлять:
После изменений запускайте:
```bash
git add .
git commit -m "Описание изменений"
git push
```

## 🎨 Для публикации сайта (GitHub Pages):
1. Зайдите в Settings репозитория
2. Слева выберите "Pages"
3. Source: main branch
4. Folder: /dist
5. Сохраните
6. Сайт будет доступен по адресу: `https://YOUR_USERNAME.github.io/gamesfast-store/`

---

**Примечание:** Локальный сервер уже запущен на http://localhost:8000

