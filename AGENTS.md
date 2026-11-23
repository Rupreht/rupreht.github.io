# AGENTS.md

`README.md` в этом репозитории генерируется: следующая публикация перезапишет правки в нём.

- Оформление страницы - `_templates/readme.md.tmpl`, логика сборки - `bin/render-readme`.
- Содержание - канон `DevOpsEngineer.senior.md` в репозитории `my`, здесь его нет.
- Проверка перед коммитом: `bin/render-readme ../my/DevOpsEngineer.senior.md --check` и `markdownlint-cli2 README.md`.
- Длинное тире запрещено, ставится дефис-минус.
- Jekyll публикует любой корневой markdown как страницу, поэтому служебные файлы добавляются в `exclude` в `_config.yml`.
