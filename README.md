# Lingua — Твой Discord помощник

<img src="lingua.png" alt="Логотип" style="float: right; width: 200px;"/>

Централизация чаще всего зло, поэтому теперь этот бот — полностью open-source.

## 📌 Возможности
- Отвечает на вопросы с помощью AI.
- Поддержка OpenAI / OpenRouter.
- Минималистичный, без лишних зависимостей.

## 🚀 Установка

1. **Клонируйте репозиторий**
   ```bash
   git clone git@github.com:atarwn/Lingua.git
   cd Lingua
   ```
   
2. **Создайте и активируйте виртуальное окружение**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Для bash/zsh
   ```

   _Для других оболочек:_
   ```bash
   source .venv/bin/activate.fish  # Fish
   source .venv/bin/activate.csh   # CSH/TCSH
   source .venv/bin/activate.bat   # Windows CMD
   source .venv/bin/activate.ps1   # PowerShell
   ```

3. **Установите зависимости**
   ```bash
   pip install -r req.txt
   ```

4. **Заполните файл `.env`**
   ```ini
   BOT = MTqVsuPerSeCREtbOtToken
   OAI = sk-supersecretopenaitoken
   API = https://openrouter.ai/api/v1
   ```

   > *Примечание:* Ключи здесь невалидные, замените их на свои.

5. **Запустите бота**
   ```bash
   python app.py
   ```

## 🤝 Участие в проекте

Хотите помочь? Отлично!
- Присылайте PR с исправлениями или фичами.
- Оставляйте [issues](https://github.com/atarwn/Lingua/issues).
- Пишите предложения.

## 📝 Лицензия

Проект распространяется под [Qwaderton License](LICENSE).
