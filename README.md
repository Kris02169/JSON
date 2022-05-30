# JSON
 4. Создать внешний репозиторий c названием JSON.
#Open github
#Repositories-New-JSON-Create repository

 5. Клонировать репозиторий JSON на локальный компьютер.
#Open JSON-Code- Copy
#Open gitbash
git clone https://github.com/Kris02169/JSON.git

 6. Внутри локального JSON создать файл “new.json”.
cd JSON
touch new.json

 7. Добавить файл под гит.
git add new.json

 8. Закоммитить файл.
git commit -m "New file"

 9. Отправить файл на внешний GitHub репозиторий.
git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
cat >> new.json
{ 
"Name":"Kristina",
"Age": 26,
"Pets": 0,
"Salary": 500
}
ctrl+c

 11.Отправить изменения на внешний репозиторий.
git add new.json; git commit -m "Update"; git push

 12.Создать файл preferences.json
cat > preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
cat >> preferences.json
{ 
"Movie":"Meet Joe Black: Sooner or Later Everyone Does",
"Serial":"How a need your mother",
"Food":"Cake",
"Season":"Summer"
}
ctrl+c

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >> sklls.json 
{
"skills":[
"1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.)", SDLC, STLC.
"2. Что такое клиент-серверная архитектура.",
"3. HTTP Методы запросов на сервер.",
"4. Коды ответов HTTP сервера.",
"5. Структуры HTTP запросов и ответов.",
"6. Что такое JSON, XML. Их структура.",
"7. Тестирование API через Postman (JS, автотесты API).",
"8. Снятие и чтение логов c внешнего сервера.",
"9. Снифинг http web трафика через Charles и Fiddler.",
"10. Dev Tools веб браузеров (Google Chrome, FireFox).",
"11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
"12. Мобильное тестирование.",
"13. Особенность iOS, Android, гайдлайны.",
"14. Сборка iOS приложений на XCode.",
"15. Сборка Android приложений на Android Studio.",
"16. ADB (управление андройд девайсами).",
"17. Настройка прокси и vpn на iOS и Android.",
"18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
"19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
"20. Основы bash скриптинг, автоматизация рутинных задач на сервере.",
"21. Доступ к удалённым серверам.",
"22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
"23. База данных Postgres (установка, настройка и использование).",
"24. Нереляционная база данных Redis (установка, настройка и использование).",
"25. Нагрузочное тестирование в Jmeter.",
"26. Методология разработки Scrum"]
}
ctrl+c

 15. Отправить сразу 2 файла на внешний репозиторий.
git add .; git commit -m "New files"; git push

 16. На веб интерфейсе создать файл bug_report.json.
#Add file -Create new file - bug_report.json

 17.Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Commit new file

 18.На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
#bug_report.json-edit this file
{
"Bug_id":1,
"Title":"The 'pay' button is missing",
"Severity":"major",
"Priority":"high",
"Precondition":["1.Payment page.","2.Platform and device don't matter."],
"Step to reproduce":["1.Log in","2.Add item to cart.","3.Click the pay button."],
"AR":"The 'pay' button is missing.",
"ER":"You can click on 'pay' button",
"Attachments":"https://drive.google.com/file/"
}

 19.Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Commit canges

 20.Синхронизировать внешний и локальный репозиторий JSON
 git pull
