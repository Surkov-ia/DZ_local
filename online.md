# GIT. **Краткое руководство**
* ## Lockal repasitoriy

1. git init - создание локального рипазитория в выбраной папке
2. git add "название фаила" - записать изменение в фаил
3. git commit -m "коментарий" - добавить коментарий к сохраненному изменению
4. git remote add origin - ? 
5. git push -u origin master - ?
6. git log --oneline - просмотреть все коммиты
7. git checkout . - восстановить все
8. git checkout "код коммита" - вернутся до состояния этого коммита
9. git checkout master - вернутся в ветку мастер
10. git fetch --all - восстановить файлы на локальном компьютере
11. git reset --hard origin/master - ?
12. git reset --hard - отмена коммита
13. git add text.txt - добавить фаил в репозиторий
14. git rm text.txt - удалить фаил
15. git status - текущее состояние репозитория
16. git commit -a -m "коментарий" - сделать комит 
17. git push origin - Замерджить все ветки локального репозитория на удаленный репозиторий
18. git push origin master - Аналогично предыдущему, но делается пуш только ветки master
19. git push origin HEAD - Запушить текущую ветку, не вводя целиком ее название
20. git pull origin - Замерджить все ветки с удаленного репозитория
21. git pull origin master - Аналогично предыдущему, но накатывается только ветка master
22. git pull origin HEAD - Накатить текущую ветку, не вводя ее длинное имя
23. git fetch origin - Скачать все ветки с origin, но не мерджить их в локальный репозиторий
24. git fetch origin master - Аналогично предыдущему, но только для одной заданной ветки
25. git checkout -b some_branch origin/some_branch - Начать работать с веткой some_branch (уже существующей)
26. git branch some_branch - Создать новый бранч (ответвится от текущего)
27. git checkout some_branch - Переключиться на другую ветку (из тех, с которыми уже работаем)
28. git branch # звездочкой отмечена текущая ветвь - Получаем список веток, с которыми работаем
29. git branch -a # | grep something - Просмотреть все существующие ветви
30. git merge some_branch - Замерджить some_branch в текущую ветку
31. git branch -d some_branch - Удалить бранч (после мерджа)
32. git branch -D some_branch - Просто удалить бранч (тупиковая ветвь)
33. git show d8578edf8458ce06fbc5bb76a58c5ca4a58c5ca4 - Изменения, сделанные в заданном коммите
34. git push origin :branch-name - Удалить бранч из репозитория на сервере
35. git reset --hard d8578edf8458ce06fbc5bb76a58c5ca4a58c5ca4 - Откатиться к конкретному коммиту и удалить последующие (хэш смотрим в «git log»)
36. git push -f - залить на сервер измененные коммиты
37. git clean -f - Удаление untracked files