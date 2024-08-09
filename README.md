#### Создала my_first_repository-

#### Additional Options + 

#### Дополнительные опции +.

|**Git Config**  |**Git Конфигурация**|
|----------------|---------------------|

|   **Git Terminal command**     |    **Команда Терминала Git**
|--------------------------------|--------------------------------|
|`git config --global user.name` |`git config --global user.имя`  |  
|`git config --global user.email`|`git config --global user.почта`|

|**Change directory command** |**Команда изменения директории**|
|-----------------------------|--------------------------------|
|`git cd c:\folder_name`      |`git cd c:\Имя_папки`           |

|**Current directory display command** |**Команда отображения текущей директории**|
|--------------------------------------|------------------------------------------|
|MacOS, Linux:  `pwd`                  |MacOS, Linux:  `pwd`                      |
|Windows:  `cd`                        |Windows:  `cd`                            |

|**Command listing  current directory**| **Команда листинг текущий директории**   |
|--------------------------------------|------------------------------------------|
|MacOS, Linux: `ls`                    |MacOS, Linux: `ls`                        |
| Windows: `dir`                       |Windows: `dir`                            |

|**Initialise folder command**| **Команда инициализации папки**|
|-----------------------------|--------------------------------|
|`git init`                   | `git init`                     |

|**Checking git version** | **Проверка версии git** |
|-------------------------|-------------------------|
|`git --version`          | `git --version`         |

| **File delete command**      |**Команда удаление файла**      |
|------------------------------|--------------------------------|
|MacOS, Linux: `rm <name_file>`|  MacOS, Linux: `rm <имя_файла>`|
|Windows: `del <name_file>`    |  Windows: `del <имя_файла>`    |

|**Command current repository status** | **Команда текущего состояния репозитория** |
|--------------------------------------|--------------------------------------------|
| `git status`                         | `git status`                               |

| **Comment creation command**                         | **Команда создания комментария**                             |
|------------------------------------------------------|--------------------------------------------------------------|
| `git add` - add all changes in the current directory |`git add` - для добавления всех изменений в текущей директорию|
| `git add "name_file"` -  add a specific file         |`git add "имя_файла"` - для добавления конкретного файла      | 

| **Command commit to save changes to repository**                     | **Команда фиксация сохранения изменений в репозитории**             |
|----------------------------------------------------------------------|---------------------------------------------------------------------|
|`git commit -m "comment message"` Creating a comment with a message   | `git commit -m "Сообщение коммента"` Создание коммента с сообщением |
|`git commit --amend` - Correcting the last comment                    | `git commit --amend` - Исправление последнего коммента              |

|**Command  view states in repository**                                   |  **Команда просмотр состояниями в репозитория**                        |
|-------------------------------------------------------------------------|------------------------------------------------------------------------|
|Comparison with the last comment: `git diff`                             |Сравнение с последним комментом: `git diff`                             |
|View the differences between two comments: `git diff "commit1" "commit2"`|Просмотр различий между двумя комментами: `git diff "commit1" "commit2"`|
|View differences for a specific: `it diff "name_file"`                   |Просмотр различий для конкретного файла: `git diff "имя_файла"`         |

|**Command for switching between branches**                               |   **Команда для переключения между ветками**                             |
|-------------------------------------------------------------------------|--------------------------------------------------------------------------|
|Switching to another branch: `git checkout "branch"`                     |Переключение на другую ветку: `git checkout "branch"`                     |
|Creating a new branch and switching to it: `git checkout -b "new_branch"`|Создание новой ветки и переключение на неё: `git checkout -b "new_branch"`|
|Switch to a specific commit: `git checkout "commit"`                     |Переключение на определённый коммит: `git checkout "commit"`              |

<<<<<<< HEAD
|**Command for managing branches in a repository**                  |   **Команда для управления ветками в репозитории**                  |
|-------------------------------------------------------------------|---------------------------------------------------------------------|
|Viewing a list of branches: `git branch`                           |Просмотр списка веток: `git branch`                                  |
|Creating a new branch: `git branch "new_branch_name"`              |Создание новой ветки: `git branch "имя_новой_ветки"`                 |
|Deleting a branch: `git branch -d "branch_name"`                   |Удаление ветки: `git branch -d "имя_ветки"`                          | 
|Forcibly deleting a branch: `git branch -D "branch_name"`          |Принудительное удаление ветки: `git branch -D "имя_ветки"`           |
|Renaming a branch: `git branch -m "old_name" "new_name"`           |Переименование ветки: `git branch -m "старое_имя" "новое_имя"`       |
|Viewing deleted branches: `git branch -r`                          |Просмотр удаленных веток: `git branch -r`                            |
|Viewing all branches (local and deleted): `git branch -a`          |Просмотр всех веток (локальных и удаленных): `git branch -a`         |
|Create a branch and switch to it: `git branch -b "new_branch_name"`|Создание ветки и переключение на нее: git branch -b "имя_новой_ветки"|
=======
|**Command for managing branches in a repository**                    |   **Команда для управления ветками в репозитории**                    |
|---------------------------------------------------------------------|-----------------------------------------------------------------------|
|View the list of branches: `git branch`                              |Просмотр списка веток:` git branch`                                    |
|Create a new branch: `git branch "new_branch_name"`                  |Создание новой ветки: `git branch "имя_новой_ветки"`                   |
|Deleting a branch: `git branch -d "branch_name"`                     |Удаление ветки: `git branch -d "имя_ветки"`                            |
|Forced deletion of a branch: `git branch -D "branch_name"`           |Принудительное удаление ветки: `git branch -D "имя_ветки"`             |
|Rename a branch: `git branch -m "old_name" "new_name"`               |Переименование ветки: `git branch -m "старое_имя" "новое_имя"`         |
|View deleted branches: `git branch -r`                               |Просмотр удаленных веток: `git branch -r`                              |
|View all branches (local and remote): `git branch -a`                |Просмотр всех веток (локальных и удаленных): `git branch -a`           |
|Create a branch and switch to it: `git branch -b "new_branch_name"`  |Создание ветки и переключение на нее: `git branch -b "имя_новой_ветки"`|
>>>>>>> Вручную добавил текст из конфликта

|**Сommand to merge changes from different branches**  |   **Команда для объединения изменений из разных веток**|
|------------------------------------------------------|--------------------------------------------------------|
|Basic merge: git merge: `"branch_name"`               |Базовое слияние: `git merge "имя_ветки"`                |

|**Command branch renaming**                                                          |  **Команда переименования ветки** |
|-------------------------------------------------------------------------------------|-----------------------------------|
|If you are in the branch you want to rename: `git branch -m new_branch_name`         |Если вы находитесь в ветке, которую хотите переименовать: `git branch -m новое_имя_ветки`|
|If you want to rename another branch: `git branch -m old_branch_name new_branch_name`|Если вы хотите переименовать другую ветку: `git branch -m старое_имя_ветки новое_имя_ветки`|