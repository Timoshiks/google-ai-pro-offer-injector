# Google AI Pro Offer Injector

Chrome-расширение для тестирования и инъекции offer token в Google One / AI Pro.

## Структура проекта

- `manifest.json` — конфигурация расширения (Manifest V3)
- `content.js` / `inject.js` — скрипты инъекции для `one.google.com`
- `play_guard.js` — вспомогательный скрипт для `play.google.com`
- `popup.html` / `popup.js` — интерфейс управления слоями инъекции
- `icons/` — иконки расширения

## Установка расширения в Chrome

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/Timoshiks/google-ai-pro-offer-injector.git
   ```
2. Откройте в Chrome страницу управления расширениями: `chrome://extensions/`
3. Включите **«Режим разработчика»** (Developer mode) в правом верхнем углу.
4. Нажмите **«Загрузить распакованное расширение»** (Load unpacked) и выберите папку проекта.
