# HW_2 : JSON

1. Создать внешний репозиторий c названием JSON;

2. Клонировать репозиторий JSON на локальный компьютер - `git clone URL`;
 
3. Внутри локального JSON создать файл “new.json” - `touch new.json`;
 
4. Добавить файл под гит - `git add .`; 
 
5. Закоммитить файл - `git commit -m "new file"`;
 
6. Отправить файл на внешний GitHub репозиторий `git push`;
 
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, 
    количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:

```
{
	"info":
	{
		"about_me":
			{
				"name" : "Vitaly",
				"lastname" : "Krivoruchek",
				"age" : 23,
				"pets" : 3
			},

		"work":
			{
				"position" : "QA Engineer",
				"salary" : 600,
				"currency" : "USD"
			}
	}
}	
```

8. Отправить изменения на внешний репозиторий - `git commit -am "updated file" / git push`;
 
9. Создать файл preferences.json - `touch preferences.jsone`;
 
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:

```
{
    "preference":
        {
            "favorite_movie" : "Волк с Уолл-стрит",
            "favorite_series" : "Сотня",
            "favorite_food":
                [
                    "Окрошка",
                    "Жареная картошка"
                ],

            "favorite_season":
                [
                    "Лето",
                    "Осень"
                ],

            "favorite_countries":
                [
                    "Швейцария",
                    "Канада"
                ]
        }
}
```
 
11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON - `touch skils.json`:

```
{
    "skills":
        {
            "1" : "Базовая теория",
            "2" : "Что такое клиент-серверная архитектура",
            "3" : "HTTP Методы запросов на сервер",
            "4" : "Коды ответов HTTP сервера",
            "5" : "Структуры HTTP запросов и ответов",
            "6" : "Что такое JSON, XML. Их структура",
            "7" : "Тестировнаие API через Postman (JS, автотесты API)",
            "8" : "Снятие и чтение логов с внешнего сервера",
            "9" : "Снифинг http web трафика через Charles и Fiddler",
            "10" : "Dev Tools веб браузеров (Google Chrome, FireFox)",
            "11" : "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
            "12" : "Мобильное тестирование",
            "13" : "Особенность iOS, Android, гайдлайны",
            "14" : "Сборка iOS приложений на XCode",
            "15" : "Сборка Android приложений на Android Studio",
            "16" : "ADB (управление андройд девайсами)",
            "17" : "Настройка прокси и vpn на iOS и Android",
            "18" : "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
            "19" : "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
            "20" : "Основы bash скриптинг, автоматизация рутинных задач на сервере",
            "21" : "Доступ к удалённым серверам",
            "22" : "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
            "23" : "База данных Postgres (установка, настройка и использование)",
            "24" : "Нереляционная база данных Redis (установка, настройка и использование)",
            "25" : "Нагрузочное тестирование в Jmeter",
            "26" : "Методология разработки Scrum"
        }
}
```

12. Отправить сразу 2 файла на внешний репозиторий - `git add . / git commit -am "new 2 files" / git push`;
 
13. На веб интерфейсе создать файл bug_report.json;
 
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе;
 
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:

```
{
	"bug_report":
		{
			"project" : "Заметки",
			"version" : "1.3",
			"id" : "№5",
			"summary" : "При клике на кнопку фильтрации 'A to Z' на главной странице приложения происходит хаотичная фильтрация списков",
			"step_to_reproduce":
				[
					"1. Открыть приложение 'Заметки'",
					"2. Создать 15 списков, которые будут начинаться соответственно (A, a, D, 3, :, U, u, Ш, ш, 5, @, Ї, ї, -, d)",
					"3. На главной странице приложения ликнуть на кнопку фильтрации 'A to Z'"
				],
			"actual result" : "Списки сортируются хаотично",
			"expected result": 
				[
					"Списки сортируются по порядку: символы, цифры, буквы латиницы (сначала верхний регистр), буквы кириллицы (сначала верхний регистр)",
					"Правильный порядок : (-, :, @, 3, 5, А, а, D, d, U, u, Ї, ї, Ш, ш)"
				],
			"severity" : "Minor",
			"priority" : "Normal",
			"status" : "New",
			"environment" : "IPhone 7 Plus, version 15.4.1",
			"author" : "Vitaly",
			"assignee" : "Ivan",
		}
}
```
 
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе;
 
27. Синхронизировать внешний и локальный репозиторий JSON - `git pull`.
