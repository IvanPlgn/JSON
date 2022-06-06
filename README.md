  JSON

Создать внешний репозиторий c названием JSON.
repositories - new

Клонировать репозиторий JSON на локальный компьютер.
git clone + ключ ssh 

Внутри локального JSON создать файл “new.json”.
touch new.json

Добавить файл под гит.
git add new.json

Закоммитить файл.
git commit -m "add first file"

Отправить файл на внешний GitHub репозиторий.
git push

Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
cat >> new.json
{
"Full name": "Don Simon",
"Age": 34,
"Number of pets": 1,
"Future desired salary": 100000
}
CTRL+D

Отправить изменения на внешний репозиторий.
git add . ; git commit -m "changes json file" ; git push

Создать файл preferences.json
touch preferences.json

В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
cat >> preferences.json
{
"Favorite movie": "RocknRolla",
"Favourite TV show": "Top Gir",
"Favorite food": "Bolognese",
"Favorite time of year": "Summer",
"Country to which. would like to visit": "USA"
}
CTRL+D

Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >> skills.json
{
"Skills": "Linux, Bash, Git, GitHub, API, HTTP/HTTPS, SQL"
}
CTRL+D

Отправить сразу 2 файла на внешний репозиторий.
git add . ; git commit -m "add two files" ; git push

На веб интерфейсе создать файл bug_report.json.
Создать файл в GitHub bug_report.json

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Файл bug_report. json закоммитить в GitHub

На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
Модифицировать в GitHub файл bug_report.json
{
  "ID": "1",
  "Reporter": "Ivan Pl",
  "Title": "The order of the icons is restored to the default on the main screen after a few taps on the "Add widget" button",
  "Severity": "major",
  "Priority": "high",
  "Environment": "Huawei p10 lite (WAS LX-1), Android 8.0.0",
  "Precondition": "The icons of other applications is located on the home screen",
  "STR": "1) Open the "Android grit test" app. 2) Tap a few times on the "Add widget" button. 3) Pay attention to the icons on the main screen",
  "AR": "The order of the icons is restored to the default on the main screen after a few taps on the "Add widget" button",
  "ER": "The icons of other applications remained in their places on the main screen after few taps on the "Add widget" button",
  "Attachments": "https://drive.google.com/file/d/1UQNpWUXDhgvTwpYkfbKx-fcHFJZWH2_E/view?usp=drivesdk"
}

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сделать коммит bug_report.json

Синхронизировать внешний и локальный репозиторий JSON
git pull
