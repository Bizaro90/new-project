Для того щоб створити такий самий репозиторій для себе необхідно зробити наступне:
1. Створити аккаунт на GitHub
2. Створити новий репозиторій 
3. Встановити Git на ПК з якого Ви будете працювати
4. Створити директорію в якій будете зберігати файли для свого проекту і перейти в цю директорію в терміналі.
5. Виконати команду git init, цим самим створивши локальний репозиторій.
6. Додати віддалений репозиторій командою git remote add origin https://github.com/Bizaro90/new-project.git (де https://github.com/Bizaro90/new-project.git - це посилання на репозиторій створений на другому кроці) 
7. Створити файл Readme.md і додати початковий текст до нього.
8. Додати файл до відстеження системою Гіт командою git add .\README.md (де .\README.md це шлях до файлу) 
9. Зробити перший коміт у системі Git командою git commit -m "init"
10. Перенести початкову версію локального репозиторію у віддалений репозиторій командою git push --set-upstream origin main
11. Створити і перейти в нову гілку, в цьому випадку для наповненя файлу Readme, командою git checkout -b development (де development - це назва нової гілки)
12. Наповнити файл Readme змістом
13. Зберегти зміни до файлу у системі гіт командою git commit -am "створення інструкції у файлі Readme". В цій команді ключ -am відповідає за додавання до коміту всіх файлів, які вже відстежуються системою Git, а в лапках - коментар до коміту.
14. Перенести поточний стан файлу Readme у віддалений репозиторій у гілку development. Команда для цього - git push --set-upstream origin development
15. Об'єднати гілки development з основною. Для цього перейти в гілку main командо git checkout main ; Виконати злиття командою git merge development
16. Перенести поточний стан локального репозиторію у віддалений командою git push

__________________________________________________________________________________________________________________________________________________________________________________

In order to create the same repository for yourself, you need to do the following:
1. Create an account on GitHub
2. Create a new repository
3. Install Git on the PC from which you will work
4. Create a directory in which you will save files for your project and go to this directory in the terminal.
5. Run the git init command, thereby creating a local repository.
6. Add the remote repository with the command git remote add origin https://github.com/Bizaro90/new-project.git (where https://github.com/Bizaro90/new-project.git is a link to the repository created on the second steps)
7. Create the Readme.md file and add the initial text to it.
8. Add the file to be tracked by the Git system with the command git add .\README.md (where .\README.md is the path to the file)
9. Make the first commit in the Git system with the command git commit -m "init"
10. Transfer the initial version of the local repository to the remote repository with the command git push --set-upstream origin main
11. Create and switch to a new branch, in this case to fill the Readme file, with the command git checkout -b development (where development is the name of the new branch)
12. Fill the Readme file with content
13. Save changes to the file in the git system with the command git commit -am "creating instructions in the Readme file". In this command, the -am key is responsible for adding to the commit all files that are already tracked by the Git system, and in quotes - a comment to the commit.
14. Transfer the current state of the Readme file to the remote repository in the development branch. The command for this is git push --set-upstream origin development
15. Combine the development branch with the main one. To do this, go to the main branch with the git checkout main command; Execute the merge with the git merge development command
16. Transfer the current state of the local repository to the remote one using the git push command