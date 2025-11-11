# LR6
Лабораторная работа №6

Для выполнения работы были проделаны действия:
1. Использован личный созданный аккаунт github
![[Screenshot 2025-11-11 142803.png]]
2. 

Лог команд:
```git checkout master
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
```

3. Установлен Git
![[Screenshot 2025-11-11 145546.png]]

4. Настроен клиент git
![[Screenshot 2025-11-11 145920.png]]

5. Репозиторий склонирован на пк
![[Screenshot 2025-11-11 150018.png]]

6. Добавлен файл через интерфейс GitHub и подтянуты изменения в репозиторий с помощью команды git pull
![[Screenshot 2025-11-11 150148.png]]
![[Screenshot 2025-11-11 151344.png]]

7. Получена история операций для каждой из веток с помощью команды  git log --oneline --graph --all
![[Screenshot 2025-11-11 151458.png]]

8. Просмотрены последние изменения с помощью команды git status git log --oneline
![[Screenshot 2025-11-11 151531.png]]

9. Выполнено слияние и разрешён конфликт
![[Pasted image 20251111151716.png]]

10. Удалена побочная ветка
![[Screenshot 2025-11-11 151808.png]]

11. Сделаны и зафиксированы изменения
![[Screenshot 2025-11-11 151932.png]]

12. Сделан откат коммита
![[Screenshot 2025-11-11 152023.png]]

13. Создана ветка для отчёта с помощью команды git checkout -b report
![[Screenshot 2025-11-11 152100.png]]



