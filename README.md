# capture-visualizer — скилл для Claude

Профессиональная шпаргалка для [Claude Code](https://claude.com/claude-code) / Claude Desktop по световой визуализации в **Capture** (2022–2026) и сценическим конструкциям:

- Capture: система координат, интерфейс и хоткеи, импорт моделей (SketchUp, DWG, MVR…), патч, экспорт в grandMA2/MA3, связь с пультами, производительность, управление через computer use;
- фермы Prolyte: таблицы нагрузок, правила конструирования, строповка, моторы (BGV D8/D8+/C1), формулы реакций и бриделей, осмотр и отбраковка;
- Layher Allround: узлы, ригели, решётчатые балки, домкраты, ориентиры по нагрузкам;
- площадки и развесы: как читать техпак, данные по риггингу арен, штатный свет, типовые туровые развесы, чек-лист.

Язык скилла — русский.

## Установка

Скопируйте папку `capture-visualizer` в каталог скиллов:

- Claude Code: `~/.claude/skills/capture-visualizer/SKILL.md`
- Claude Desktop / claude.ai: заархивируйте папку `capture-visualizer` в ZIP и загрузите в Settings → Capabilities → Skills.

```bash
git clone https://github.com/samael4279/capture-visualizer-skill.git
cp -r capture-visualizer-skill/capture-visualizer ~/.claude/skills/
```

## Отказ от ответственности

Расчёты по фермам и риггингу в скилле — инженерная оценка для проектирования и проверки здравым смыслом. Финальные значения берутся из актуальных таблиц производителя, а конструкции подтверждают инженер-конструктор и ответственный риггер площадки.
