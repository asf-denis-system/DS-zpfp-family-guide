# Руководство «Нулевые и первые принципы для семьи»

> Прикладное руководство для взрослого, который хочет выращивать у ребёнка 3-10 лет мышление из нулевых и первых принципов — через короткие бытовые эпизоды, без превращения детства в бесконечные уроки.

## Статус

**v2.4 — слои сведены** (2026-04-02)

- [x] Структура модулей согласована ([docs/module-structure.md](docs/module-structure.md))
- [x] Тексты модулей m0-m7 ([guide/](guide/))
- [x] M3 углублён: 8 принципов с примерами эпизодов, бытовыми доменами, Guard Policy, поломками
- [x] Практические примеры: заполненный лог (M2), Mastery Map (M4), недельный план (M5)
- [x] Карточки эпизодов: Z2, Z0, Z3 × 3 зоны × 2 трека ([cards/](cards/))
- [x] Промпты для бота: скрипт эпизода, анализ лога, стратегия ([prompts/](prompts/))
- [x] docs/ консолидирован: рабочие заметки в archive, ключевые документы на месте

## Структура программы

| Модуль | Что | Строк | Статус |
|--------|-----|-------|--------|
| [0. Онбординг](guide/m0-onboarding/README.md) | Контекст семьи, замер, стратегия | 167 | MVP |
| [1. Фундамент](guide/m1-foundation/README.md) | Зачем ZP детям, роли, карго-культ | 120 | MVP |
| [2. Метод](guide/m2-method/README.md) | Протокол 7 шагов, треки, пример лога | 394 | MVP |
| [3. Принципы](guide/m3-principles/README.md) | 8 ZP: эпизоды, домены, Guard Policy, поломки | 659 | MVP |
| [4. Оценка](guide/m4-assessment/README.md) | Mastery Map, Guard Policy, 10 FM, пример карты | 533 | MVP |
| [5. Стратегия](guide/m5-strategy/README.md) | Стратегия, программа, план, пример плана | 293 | MVP |
| [6. Контексты](guide/m6-contexts/README.md) | Садик, школа, кружки, безопасность | 257 | MVP |
| [7. Следующий виток](guide/m7-next-spiral/README.md) | Культура семьи, углубление ZP, мост к FP | 264 | MVP |

## Карточки и промпты

| Артефакт | Что | Файлы |
|----------|-----|-------|
| [Карточки эпизодов](cards/) | Готовые рецепты: Z2, Z0, Z3 × 3 зоны × 2 трека (18 карточек) | cards/ |
| [Промпты для бота](prompts/) | Генерация скриптов, анализ логов, стратегия | prompts/ |

## Проектные документы

| Документ | Что |
|----------|-----|
| [module-structure.md](docs/module-structure.md) | Структура модулей для Церена (WP-149) |
| [project-engineering-chain.md](docs/project-engineering-chain.md) | Инженерная цепочка проекта |
| [project-operating-model](docs/project-operating-model-2026-04-01.md) | Операционная модель |
| [onboarding-lev](docs/onboarding-lev-2026-03.md) | Онбординг Льва (пилот) |

## Связи

- **Pack:** [PACK-kids-learning](https://github.com/asf-denis-system/PACK-kids-learning) — source-of-truth
- **Curriculum:** [DS-principles-curriculum](https://github.com/aisystant/DS-principles-curriculum) — ячейки ZP по Bloom
- **Бот:** DS-personal-bot (тестовый модуль fpfkids)
- **Стратегия:** DS-strategy/inbox/WP-W15-zpfp-family-guide-bot.md

## Авторы

Д. Асфандияров, L. Samer. При поддержке Ц. Церенова и сообщества МИМ.
