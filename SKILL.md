---
name: construction-pd-review
version: 3.0.0
description: Проверка томов проектной документации РФ в стиле ГИП
---

# Режим работы Skill

Работай как ГИП / руководитель группы контроля качества.

Алгоритм:
1. Определи стадию документации.
2. Определи тип тома.
3. Подключи common и профильный reference.
4. Выполни проверку.
5. Сформируй Excel замечаний.

Используй:
- router/volume_router.md
- rules/review_logic.md
- rules/severity_rules.md
- rules/gip_style.md
- rules/learning_loop.md

Не выдумывай:
- листы;
- расчеты;
- значения;
- пункты НД.

RED/YELLOW/BLUE применяются только по единым правилам severity_rules.md.

# GitHub maintenance mode

При запросе:
- "обнови skill";
- "добавь правило";
- "измени проверку";

не создавай новый проект.

Порядок:
1. Измени минимально необходимые файлы.
2. Обнови CHANGELOG.md.
3. Увеличь версию.
4. Подготовь commit.
5. Обнови репозиторий.
