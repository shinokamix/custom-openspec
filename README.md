# Custom OpenSpec

Упрощённый набор действий OpenSpec для Codex и Claude Code.

Доступны три действия:

| Действие | Codex | Claude Code |
| --- | --- | --- |
| Создать план изменения | `$openspec-propose` | `/opsx:propose` |
| Выполнить задачи | `$openspec-apply-change` | `/opsx:apply` |
| Закрыть изменение | `$openspec-archive-change` | `/opsx:archive` |

Схема `spec-driven` создает два артефакта:

- `specs/**/*.md` с требованиями, сценариями и общими контрактами;
- `tasks.md` с проверяемым планом реализации.

Документы пишутся по-русски. Служебные маркеры OpenSpec, включая
`Requirement`, `Scenario`, `WHEN` и `THEN`, остаются на английском.
