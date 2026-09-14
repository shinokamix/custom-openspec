# Custom OpenSpec

Упрощённый набор действий OpenSpec для Codex и Claude Code.

Доступны три действия:

| Действие | Codex | Claude Code |
| --- | --- | --- |
| Создать план изменения | `$openspec-propose` | `/opsx:propose` |
| Выполнить задачи | `$openspec-apply-change` | `/opsx:apply` |
| Закрыть изменение | `$openspec-archive-change` | `/opsx:archive` |

Проект использует исходную схему `spec-driven`. Шаблоны `proposal.md`, `spec.md`, `design.md` и `tasks.md` пока не изменены.
