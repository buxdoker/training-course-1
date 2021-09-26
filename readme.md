
1. https://git-scm.com/download/win
2. Установить https://nodejs.org/uk/
3. Установить https://www.npmjs.com/package/npm: в Терминал редактора VScode скопировать и запустить (Enter) curl -qL https://www.npmjs.com/install.sh | sh
4. Потом зайти в директорию, где ты хочешь создать свой новый проект и выполнить команду git clone
5. Потом запустить установку нужных пакетов для работы. Внутри используется сборщик parsel https://v2.parceljs.org/getting-started/webapp/ :

# npm install

6. Запустить локальный сервер для компилирования и отображения кода из директории src/

# npm run start

7. Основные команды git

## git clone
## git status
## git add .

## git commit -m "text of the commit" 
or with adding new files:
## git commit -am "text of the commit"

## git pull
## git push 

Создать новую ветку и перейти в нее
## git checkout -b relevant-name-of-branch

Перейти в уже существующую ветку (без параметра -b)

## git checkout relevant-name-of-branch