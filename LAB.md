# LAB — день 8

> Скопируйте в `LAB.md` в корне `git-bootcamp-day-8` на **GitHub** и заполните по ходу работы.

## Базовая задача — `01-pr-and-review`

### Ссылки

| Что | URL |
|-----|-----|
| Репозиторий | [FIXME: https://github.com/.../git-bootcamp-day-8] |
| Issue | [FIXME: https://github.com/.../git-bootcamp-day-8/issues/N] |
| Pull Request | [FIXME: https://github.com/.../git-bootcamp-day-8/pull/N] |

### Скриншоты (обязательные)

1. **Issue** — страница с текстом задачи:

![Issue](screenshots/issue.png)

2. **История feature-ветки** — `git log --oneline feature/<slug>`, видны 3 CC-коммита:

![Feature branch log](screenshots/feature-log.png)

3. **Pull Request** — заполненный template (Описание / Что меняется / Как проверять / Чек-лист):

![Pull Request](screenshots/pull-request.png)

4. **Привязка к Issue** — `Closes #N` в описании или блок Linked issues:

![Linked issue](screenshots/linked-issue.png)

### Скриншоты (опциональные)

5. **Protection rules** на `main` (если настраивали):

![Branch protection](screenshots/branch-protection.png)

6. **Ревью чужого PR** — ваши комментарии + ссылка на PR:

![Review comments](screenshots/review-comments.png)

Ссылка на чужой PR: [FIXME]

### Команды

```bash
# git switch -c feature/<slug>
# git add … && git commit -m "feat(...): …"
# git add … && git commit -m "test(...): …"
# git add … && git commit -m "docs: …"
# go test ./...
# git push -u origin feature/<slug>
```

### Впечатления (2–3 предложения)

[FIXME: что было непонятно при оформлении PR, что узнали нового]

### Ревью чужих PR (опционально)

Ссылки на PR, где оставили комментарии:

- [FIXME: https://github.com/.../pull/N]

Кратко — что заметили (оформление, не код):

[FIXME: 1–2 предложения]

### Protection rules (опционально)

[FIXME: включали ли правила на main, что именно — 1–2 предложения]
