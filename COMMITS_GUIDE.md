# Інструкція з комітів для лабораторної роботи №1

## Підготовка (один раз)

```bash
git init
git config --global user.name "Vasyliev Bohdan"
git config --global user.email "your@email.com"
```

---

## Коміт 1 — Ініціалізація проєкту

Додати тільки .gitignore:

```bash
git add .gitignore
git commit -m "init: initialize project and add .gitignore"
```

---

## Коміт 2 — Базова структура index.html

```bash
git add index.html
git commit -m "feat: create basic index.html structure"
```

---

## Коміт 3 — Навігаційне меню (додати about.html та contacts.html БЕЗ контенту)

Спочатку створи порожні файли about.html і contacts.html з базовою структурою
(тільки DOCTYPE, head, header з nav, порожній main, footer).
Потім:

```bash
git add about.html contacts.html
git commit -m "feat: add navigation menu to all pages"
```

---

## Коміт 4 — Контент сторінки "Про мене"

Заміни about.html на повну версію з контентом (текст про себе, секції):

```bash
git add about.html
git commit -m "feat: create about.html with personal info"
```

---

## Коміт 5 — Таблиця навичок на about.html

Додай таблицю навичок до about.html (вже є в готовому файлі):

```bash
git add about.html
git commit -m "feat: add skills table to about page"
```

---

## Коміт 6 — Контактна інформація

Додай contacts.html з контактною інформацією (email, телефон):

```bash
git add contacts.html
git commit -m "feat: create contacts.html with contact info"
```

---

## Коміт 7 — Форма зворотного зв'язку

Додай форму до contacts.html (вже є в готовому файлі):

```bash
git add contacts.html
git commit -m "feat: add contact form to contacts page"
```

---

## Коміт 8 — Зображення та мультимедіа

Додай фото/зображення до папки images/, аудіо до audio/:

```bash
git add images/ audio/ about.html
git commit -m "feat: add images and multimedia elements"
```

---

## Коміт 9 — Виправлення ієрархії заголовків

Перевір усі сторінки — заголовки мають йти h1 → h2 → h3 без пропусків.
Якщо все добре, просто зроби дрібне виправлення (наприклад, уточни текст):

```bash
git add index.html about.html contacts.html
git commit -m "fix: correct heading hierarchy on about page"
```

---

## Коміт 10 — Рефакторинг семантики

Переглянь структуру, переконайся що скрізь є header/main/footer/nav:

```bash
git add .
git commit -m "refactor: improve semantic structure across all pages"
```

---

## Коміт 11 — README

```bash
git add README.md
git commit -m "docs: add README file"
```

---

## Завантаження на GitHub

```bash
git remote add origin git@github.com:ВАШ_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

---

## Перевірка

```bash
git log --oneline    # переглянути всі коміти
git status           # перевірити стан файлів
```
