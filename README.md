# HW_Branches
Homework branches
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

2. Запушить все ветки на внешний репозиторий
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
4. Запушить структуру багрепорта на внешний репозиторий
5. Вмержить ветку Bag Reports в Main
6. Запушить main на внешний репозиторий.
7. В ветке CheckLists набросать структуру чек листа.
8. Запушить структуру на внешний репозиторий
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main

Основные команды:

- Создать локальную ветку —> git branch NAME
- Перейти в ветку —> git checkout NAMe
- Создать и перейти —> git checkout -b NAME
- Посмотреть все ветки —> git branch
- Смержить ветки (объединить ветки/файлы) (main): git merge NAME
- Смержить после коммита в ветке (main): git merge NAME -m «comment»
- CONFLICT. Нужно зарезолвить —> Vim (резолвим) —> git commit -am «__»
- Добавить локальные ветки на внешний репозиторий —> git push -u origin NAME
- На внешнем репозитории  —> merge pull request

