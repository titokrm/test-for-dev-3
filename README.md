# Редактор строки с выделением и перетягиванием / String Editor with Selection and Drag-and-Drop

[Русская версия](#русская-версия) | [English version](#english-version)

---

## Русская версия

### Описание

Небольшое веб-приложение на чистом HTML/CSS/JavaScript для работы со строкой посимвольно:

- ввод строки через форму;
- выделение символов через `Ctrl + клик`;
- перетягивание выделенного символа или группы:
  - на другой символ (обмен местами);
  - между символами (вставка);
  - между разными текстовыми блоками страницы.

### Демонстрация

Интерфейс содержит несколько текстовых зон:

- заголовок;
- поясняющий текст;
- подпись поля ввода;
- заголовок результата;
- область результата (основная рабочая зона).

Именно в области результата можно выделять символы и начинать выполнение drag-and-drop операций.

### Технологии

- HTML5
- CSS3
- Vanilla JavaScript (без внешних библиотек)

### Запуск локально

1. Клонируйте репозиторий:

```bash
git clone <URL_ВАШЕГО_РЕПОЗИТОРИЯ>
```

2. Откройте файл `index.html` в браузере.

Или запустите простой локальный сервер (по желанию), например через VS Code Live Server.

### Как пользоваться

1. Введите текст в поле `Текст`.
2. Нажмите кнопку `Показати рядок` или `Enter`.
3. Зажмите `Ctrl` и кликните по символам в области результата, чтобы выделить их.
4. Перетащите выделение:
   - на символ, чтобы обменять символы местами;
   - между символами, чтобы вставить выделенный фрагмент.

### Структура проекта

```text
.
├─ index.html   # Вся разметка, стили и логика
└─ README.md
```

### Лицензия

Добавьте здесь выбранную лицензию (например, MIT), если планируете публичное использование проекта.

---

## English version

### Description

A small web app built with plain HTML/CSS/JavaScript for character-level string editing:

- input a string through a form;
- select characters with `Ctrl + click`;
- drag a selected character or group:
  - onto another character (swap);
  - between characters (insert);
  - between different text blocks on the page.

### Demo

The interface contains multiple text zones:

- title;
- hint text;
- input label;
- result title;
- result area (main working zone).

You can select characters and perform drag-and-drop operations in the result area.

### Technologies

- HTML5
- CSS3
- Vanilla JavaScript (no external libraries)

### Run locally

1. Clone the repository:

```bash
git clone <YOUR_REPOSITORY_URL>
```

2. Open `index.html` in your browser.

Or run a simple local server if needed, for example with VS Code Live Server.

### How to use

1. Enter text in the `Текст` field.
2. Click `Показати рядок` or press `Enter`.
3. Hold `Ctrl` and click characters in the result area to select them.
4. Drag the selection:
   - onto a character to swap;
   - between characters to insert the selected fragment.

### Project structure

```text
.
├─ index.html   # Markup, styles, and logic
└─ README.md
```

### License

Add your preferred license here (for example, MIT) if you plan to publish the project.
