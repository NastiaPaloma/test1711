
# Инструкция по работе с Git-командами.

***1.Проверка установки программы.***

>Прежде чем создавать репозиторий, необходимо проверить текущую установленную версию программы.

* **git --version**

***2. Инициализация репозитория.***

>Указываем папку, в которой git начнет отслеживать изменения.

* **git init**

***3. Проверка статуса репозитория.***

>Показывает текущее состояние гита, есть ли изменения, которые нужно закоммить.

* **git status**

***4. Добавление файлов.***

>Добавляет содержимое для рабочего каталога в индекс для последующего коммита.

* **git add[NameFile]**

>Добавляет все файлы проекта в наш будующей commit.

* **git add .**

***5. Зафиксировать или сохранить.***

>Фиксация изменения с соответствующим комментарием.

* **git commit -m"Comment"**

>Следующая команда позволяет сократить количество шагов сохранения при повторах.

* **git commit -am"Comment"**

***6. Журнал изменений.*** 

>Показывает количество нескольких  commit.

* **git log**

>Показывает последний commit.

* **git log -p**

>Показывае кратко все commit.

* **git reflog**

***7.Показывает изменения.***

>Показывает разницу между текущим файлом и сохранённым.

* **git diff**

>Показывает разницу между двумя commit.

* **git diff [numberCommit1] [numberCommit2}**

***8.Удаление файлов.***

>Позволяет удалять файл.

* **git rm[NameFile]**

***9.Переключение между версиями.***

>Позволяет вернуться к предыдущим версиям.

* **git checkout [numberCommit]**

>Позволяет вернуться в актуальное состояние.

* **git checkout master**