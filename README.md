# lesson-1
echo "# lesson-1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Anna-net28/lesson-1.git
git push -u origin main
# git-config
git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main
git config --global user.name “Anna Volkova”
git config --global user.email “anna35.anna35.v@gmail.com”
git config --global core.autocrlf true
git init
git status
git add .
git commit -m "проект создан"
git diff --color-words
git push
git add .
git commit -m "banner"
git diff --color-words
git push
git add .
git commit -m "header"
git diff --color-words
git push
git add .
git commit -m "header,banner,boocing,reviews изменен border у кнопок, выстроен блок отзывы flexами"
git diff --color-words
git push
git add .
git commit -m "comit"
git diff --color-words
git push
git add .
git commit -m "block,halls,header,holiday,questions,index-редактирование блоков"
git diff --color-words
git push
git add .
git commit -m "header убрала падинги, выровняла margin по центру, добавила максимальную ширину, а gap бы убран, видимо еще не прогрузились данные"
git diff --color-words
git push