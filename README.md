# Dark of the Moon

2D RPG (Godot 4.7) — меню в стиле Terraria + боевая система + мир.

## Запуск
1. Godot 4.7 → Import → `project.godot`
2. F5 → главное меню

## Меню
- Одиночная / Загрузка (6 RPG-слотов) / Новый мир
- Настройки (дисплей, звук, геймплей, доступность)
- Моды (Haster, если подключён)

## Что добавлено/восстановлено
- `Scripts/SkillSystem.gd` — скиллы 1–4
- `Scripts/InventoryUI.gd` — инвентарь (I)
- `Scripts/WorldGenerator.gd` — seed/высоты
- `Scripts/DayNightCycle.gd` — день/ночь
- `scene/menu/mega_menu.tscn` — главное меню
- Autoload: SaveSystem, GameManager

## Управление (в мире)
- A/D движение, Space прыжок, Shift рывок
- ЛКМ атака, 1–4 скиллы, I инвентарь
