# Greenleaf AI Navigator

Клиентское веб-приложение — система поддержки принятия решений для персонализации бизнес-презентаций партнёров компании Greenleaf.

## Описание

Приложение помогает начинающим партнёрам Greenleaf за 2–3 минуты получить готовый персонализированный план презентации и набор текстовых материалов (скрипт выступления, промпт для AI-аватара, пост для соцсетей) под конкретную целевую аудиторию.

## Технологический стек

- **Frontend:** React 18 + Vite
- **Роутинг:** React Router v6
- **State Management:** Zustand
- **Стилизация:** Tailwind CSS
- **Хранение данных:** localStorage + локальные JSON-моки
- **Version Control:** Git + GitHub

## Установка и запуск

```bash
# Клонировать репозиторий
git clone https://github.com/<username>/greenleaf-ai-navigator.git
cd greenleaf-ai-navigator

# Установить зависимости
npm install

# Запустить в режиме разработки
npm run dev

# Собрать production-версию
npm run build