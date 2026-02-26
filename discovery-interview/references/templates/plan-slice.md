# Template: PLAN+SLICE

```text
<proposed_plan>
## Summary
- Цель: ...
- Формат: PLAN+SLICE
- Папка плана: docs/plans/{plan_slug}/
- Итерации: SLICE1 -> SLICE2 -> SLICE3 (итеративно, не «всё сразу»)

## File index
- docs/plans/{plan_slug}/PLAN.md — индекс + рамки + метрики успеха + список слайсов
- docs/plans/{plan_slug}/SLICE1.md — 1-я итерация (заканчиваем полностью)
- docs/plans/{plan_slug}/SLICE2.md — 2-я итерация (уточняем после подтверждения SLICE1)

## self-critique
- Явное сомнение/риск: ...
- Что уточнить в следующем раунде: ...

## flagship-suggestions
- Самое сильное упрощение без потери качества: ...
- Что лучше НЕ делать в первой итерации: ...
</proposed_plan>
```

## File skeletons (copy/paste)

### docs/plans/{plan_slug}/PLAN.md

```markdown
# План: <название>

## Зачем (ценность)
<1–3 предложения>

## Рамки
- Делаем: ...
- Не делаем сейчас: ...

## Как поймём, что получилось
- Метрика/признак 1: ...
- Метрика/признак 2: ...

## Итерации (слайсы)
1. **SLICE1** — <первый проверяемый шаг>
2. **SLICE2** — <следующий шаг после подтверждения SLICE1>
```

### docs/plans/{plan_slug}/SLICE1.md

```markdown
# SLICE1 — <название итерации>

## Outcome
<что станет true после этой итерации>

## Что делаем
- ...

## Что НЕ делаем
- ...

## Как проверяем (приёмка)
- [ ] ...
- [ ] ...

## Риски и как уменьшаем
- Риск: ... → Действие: ...
```

### docs/plans/{plan_slug}/SLICE2.md (stub)

```markdown
# SLICE2 — <название>

## Depends on
- SLICE1 подтверждён

## Outcome
...
```
