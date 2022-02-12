# Выстраивание процесса непрерывной интеграции (CI): Github Actions. Покрытие кода с JaCoCo, статический анализ кода: CheckStyle, SpotBugs (Exercise_2.5.2)
## Домашнее задание по курсу "Java для тестировщиков"
## Тема: «2.5. Выстраивание процесса непрерывной интеграции (CI): Github Actions. Покрытие кода с JaCoCo, статический анализ кода: CheckStyle, SpotBugs», задание №2: «Пусть плагин ищет баги»
- Взят проект с лекции;
- Добавлены в проект JUnit Jupiter & Surefire Plugin;
- Добавлен плагин SpotBugs.
### Предварительные требования
- На компьютере пользователя должна быть установлена:
	- Intellij IDEA
### Установка и запуск
1. Склонировать проект на свой компьютер
	- открыть терминал
	- ввести команду 
		```
		git clone https://github.com/Lognestix/Exercise_2.5.2
		```
1. Открыть склонированный проект в Intellij IDEA
1. Запустить авто-тесты:
	- Нажать два раза CTRL;
	- Ввести команду 
		```
		mvn clean test
		```		