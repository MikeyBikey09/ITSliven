1. Изтегляме и инсталираме програмата GIT:
https://git-scm.com/download/win

2. Стартираме Command Prompt (WIN+R > CMD)
cd Desktop

3. За да изтеглим отдалеченото хранилище за първи път пишем:
git clone https://github.com/dimitarminchev/ITSliven.git

4. Да направим промени в локалното хранилише:
cd ITSliven
cd Names
[file].txt
git status
git add .
git pull
git commit -m "Dimitar Minchev"
git push