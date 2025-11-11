# LR6
Лабораторная работа №6

Для выполнения работы были проделаны действия:

1. Использован личный созданный аккаунт GitHub  
    ![Аккаунт GitHub](<images/Screenshot 2025-11-11 142803.png>)

2. Создана копия в личное хранилище (Fork)  
    ![Fork репозитория](<images/Screenshot 2025-11-11 154204.png>)

3. Установлен Git  
    ![Установка Git](<images/Screenshot 2025-11-11 145546.png>)

4. Настроен клиент git (имя и email)  
    ![Настройка Git](<images/Screenshot 2025-11-11 145920.png>)

5. Репозиторий склонирован на ПК  
    ![Клонирование репозитория](<images/Screenshot 2025-11-11 150018.png>)

6. Добавлен файл через интерфейс GitHub и подтянуты изменения в репозиторий с помощью команды `git pull`  
    ![Добавление файла на GitHub](<images/Screenshot 2025-11-11 150148.png>)  
    ![Подтягивание изменений git pull](<images/Screenshot 2025-11-11 151344.png>)

7. Получена история операций для каждой из веток с помощью команды  
   `git log --oneline --graph --all`  
    ![История операций](<images/Screenshot 2025-11-11 151458.png>)

8. Просмотрены последние изменения с помощью команд `git status` и `git log --oneline`  
    ![Последние изменения](<images/Screenshot 2025-11-11 151531.png>)

9. Выполнено слияние и разрешён конфликт  
    ![Разрешение конфликта](<images/Pasted image 20251111151716.png>)

10. Удалена побочная ветка  
    ![Удаление ветки](<images/Screenshot 2025-11-11 151808.png>)

11. Сделаны и зафиксированы изменения (несколько коммитов)  
    ![Фиксация изменений](<images/Screenshot 2025-11-11 151932.png>)

12. Сделан откат коммита  
    ![Откат коммита](<images/Screenshot 2025-11-11 152023.png>)

13. Создана ветка для отчёта с помощью команды `git checkout -b report`  
    ![Создание ветки report](<images/Screenshot 2025-11-11 152100.png>)

14. Получена история операций в форматированном виде  
    ![Форматированный лог](<images/Screenshot 2025-11-11 152653.png>)

15. Изменения будут отправлены в удалённый репозиторий с помощью команды `git push`.


## Лог команд

```bash
git pull
git log --oneline --graph --all
git 
git checkout master
git merge second
git checkout second
code mergefile.txt
git add .
git commit -m "feat: добавлен конфликт, теперь точно конфликт"
git checkout master
git merge second
code mergefile.txt
git add .
git commit -m "изменения в master"
git checkout second
code mergefile.txt
git add .
git commit -m "изменения в second"
code mergefile.txt
git add .
git commit -m "изменения добавлены"
git checkout master
git merge second
code mergefile.txt
git merge second
git add .
git commit -m "исправлен конфликт"
git merge second
git branch -d second
mkdir otherFile.txt
git commit -m "добавлен файл txt"
git add .
git commit -m "добавлен файл txt"
code otherFile.txt
code otherFile
git add .
git commit -m "добавлен файл txt"
dir
code mergefile.txt
git add .
git status
git commit -m "feat: изменён файл"
code textovic
git status
git add .
git commit -m "добавлен ещё важный файл"
git log --oneline
git reset --hard HEAD~1
git log --oneline
git checkout -b report
code readme.md
code report.md
doskey /history > commands.txt
