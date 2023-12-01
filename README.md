# LR6
Лабораторная работа №6

## Цель лабораторной работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы

### История операций
b35dc7b - 2023-12-01 - Matvey: mergefile updated  
d37f1d5 - 2023-12-01 - Matvey: merge problem resolved  
89707d7 - 2023-12-01 - lezhev: Add files via upload  
921f53b - 2020-11-21 - Kurtyanik: Обновление информации  
0f9f50d - 2020-11-21 - Kurtyanik: Заполнил файл  
c08a654 - 2020-11-21 - Kurtyanik: Файл создан пустым  
3c6e913 - 2020-11-21 - Kurtyanik: Initial commit  

### Лог команд
cd c:/Git  
git clone https://github.com/Lezhev/LR6  
cd lr6  
git pull  
git log --all  
git log -n 1  
git merge origin/branch1  
git status  
cat mergefile.txt  
git add .  
git commit -m "merge problem resolved"  
git push origin -d branch1  
git add .  
git commit -m "mergefile updated"  
git add .  
git commit -m "second update"  
git reset --hard HEAD~  
git checkout -b report-branch  
git log --pretty=format:"%h - %ad - %an: %s" --date=short  
git add .  
git commit -m "Added name, goal of work and histori of operations, modify readme.md"  
git add .  
git commit -m "Added screenshots"  
git add .  
git commit -m "Added log"  
git push origin report-branch  
 
### Изображения консоли

![scr 1](/scrs/Screenshot_1.png)
![scr 2](/scrs/Screenshot_2.png)
![scr 3](/scrs/Screenshot_3.png)
![scr 4](/scrs/Screenshot_4.png)
![scr 5](/scrs/Screenshot_5.png)


## Вывод: 
Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.  
