# XML
Group_30 Homework

**XML**

1. Создать внешний репозиторий c названием XML.

	  `Repositories -> New -> Repository name: XML -> Create perository`

2. Клонировать репозиторий XML на локальный компьютер.

	`git clone git@github.com:LazarevR/XML.git`

3. Внутри локального XML создать файл “new.xml”.
	```
	cd xml
	touch new.xml
	```
4. Добавить файл под гит.

	`git add new.xml`

5. Закоммитить файл.

	`git commit -m "add first new.xml file"`

6. Отправить файл на внешний GitHub репозиторий.

	`git push`

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
	```	
	<?xml version="1.0" encoding="UTF-8"?>
	<обо_мне>
		<фио>Руслан Лазарев</фио>
		<возраст>31</возраст>
		<количество_домашных_животных>0</количество_домашных_животных>
		<будущая_желаемая_зарплата>$3000</будущая_желаемая_зарплата>
	</обо_мне>
	```
8. Отправить изменения на внешний репозиторий.
	```
	git status
	git add new.xml
	git commit -m "edit the new.xml file"
	git push
	```
	Или
	```
	git checkout main
	git add new.xml
	git commit -m "edit the new.xml file"
	git push
	```
9. Создать файл preferences.xml

	`touch preferences.xml`

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
	```
	<?xml version="1.0" encoding="UTF-8"?>
	<обо_мне_2>
		<любимый_фильм>Вечное сияние чистого разума</любимый_фильм>
		<любимый_сериал>Californication</любимый_сериал>
		<любимая_еда>Солянка</любимая_еда>
		<любимое_время_года>Весна</любимое_время_года>
		<страна_которую_хотел_бы_посетить>Норвегия</страна_которую_хотел_бы_посетить>
	</обо_мне_2>
	```
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

	`touch sklls.xml`
	```
	<?xml version="1.0" encoding="UTF-8"?>
	<скиллы>
		<learn_1>Git bash/Terminal</learn_1>
		<learn_2>Git</learn_2>
		<learn_3>Postman</learn_3>
		<learn_4>Charles Proxy</learn_4>
		<learn_5>JavaScript</learn_5>
		<learn_6>SQL</learn_6>
		<learn_7>Selenium+Python</learn_7>
	</скиллы>
	```
12. Сделать коммит в одну строку.

	`git add preferences.xml sklls.xml; git commit -m "add preferences.xml, sklls.xml"`

13. Отправить сразу 2 файла на внешний репозиторий.

	`git push`

14. На веб интерфейсе создать файл bug_report.xml.

	`Repositories -> XML -> Add file -> Create new file -> "Name your file": bug_report.xml`

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	Блок "Commit new file"
	В поле заголовка: create bug_report.xml
	В поле описания: create my first but_repots.xml
	Нажать на кнопку "Commit changes"
	```
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
	```
	Repositories -> XML -> bug_report.xml -> Edit this file (иконка карандаша)
	Приступить к редактированию файла в поле "Edit file"
	```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	В поле заголовка: можно оставить пустым, а можно указать Update but_report.xml
	В поле описания: "added first bug report"
	Нажать на кнопку "Commit changes"
	```
18. Синхронизировать внешний и локальный репозиторий XML

	`git pull`
