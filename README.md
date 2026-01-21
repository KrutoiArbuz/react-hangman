# 🎯 Игра "Виселица" (Hangman)

<div align="center">
  <img src="https://img.shields.io/badge/React-19.1.1-blue?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-blue?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-7.1.7-646CFF?style=for-the-badge&logo=vite" alt="Vite" />
  <img src="https://img.shields.io/badge/ESLint-9.36.0-4B32C3?style=for-the-badge&logo=eslint" alt="ESLint" />
</div>

## 📖 Описание

Игра "Виселица" (Hangman)


## 🚀 Установка и запуск

### Предварительные требования

- Node.js (версия 16 или выше)
- npm или yarn

### Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/your-username/hangman-game.git
cd hangman-game
```

2. Установите зависимости:
```bash
npm install
```

### Запуск в режиме разработки

```bash
npm run dev
```

Откройте [http://localhost:5173](http://localhost:5173) в браузере.

### Сборка для продакшена

```bash
npm run build
```

### Предварительный просмотр сборки

```bash
npm run preview
```

## 🛠 Технологии

- **React 19**
- **TypeScript**
- **Vite**
- **ESLint**
## 📁 Структура проекта

```
hangman/
├── src/
│   ├── App.tsx              # Основной компонент приложения
│   ├── HangmanDrawing.tsx   # Компонент рисования виселицы
│   ├── HangmanWord.tsx      # Компонент отображения слова
│   ├── Keyboard.tsx         # Виртуальная клавиатура
│   ├── Keyboard.module.css  # Стили клавиатуры
│   ├── main.tsx             # Точка входа приложения
│   └── wordList.json        # Список слов для игры
├── public/
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## 🎨 Кастомизация

### Добавление новых слов

Отредактируйте файл `src/wordList.json`, добавив новые слова в массив:

```json
[
  "слово1",
  "слово2",
  "слово3"
]
```
