# Custom OpenSpec

Упрощённый набор действий OpenSpec для Codex и Claude Code.

Доступны три действия:

| Действие | Codex | Claude Code |
| --- | --- | --- |
| Создать план изменения | `$openspec-propose` | `/openspec-propose` |
| Выполнить задачи | `$openspec-apply-change` | `/openspec-apply-change` |
| Закрыть изменение | `$openspec-archive-change` | `/openspec-archive-change` |

Схема `spec-driven` создает два артефакта:

- `specs/**/*.md` с требованиями, сценариями и общими контрактами;
- `tasks.md` с проверяемым планом реализации.

Документы пишутся по-русски. На английском остаются только структурные
заголовки OpenSpec и обязательный маркер `MUST`.
