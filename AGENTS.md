## Приоритет
- Mobile-first. Посетитель с телефона за 5 секунд понимает, что вы электрик, и звонит.

## Never
- Внешние библиотеки, CDN, CSS-фреймворки (Bootstrap, Tailwind, jQuery, Google Fonts).
- `<script>` с аналитикой и трекерами.
- Дополнительные файлы (`.css`, `.js`, картинки) без явного запроса.
- `<div>` для текста, если есть семантический тег.

## Always
- Весь CSS — в `<style>` в `<head>`.
- Мобильная вёрстка, затем `@media (min-width: 768px)`.
- Интерактивные элементы — минимум 44px по высоте.
- Числовые поля — `inputmode="numeric"`.
- Внешние ссылки — `target="_blank" rel="noopener"`.
- `<html lang="ru">`.
- Без горизонтальной прокрутки: `max-width: 100%`, `box-sizing: border-box`.
- JSON-LD **LocalBusiness** (или `Electrician`): `name`, `telephone`, `address`, `areaServed`, `openingHours`.

## Границы
- ⚠️ Спросить: новая секция, смена цветовой схемы.
- ❌ Никогда: фреймворки, лишние файлы.