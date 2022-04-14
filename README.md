1. Создать внешний репозиторий c названием JSON.
 - открываем GitHub и создаем репозиторий. Копируем ссылку на репозиторий.
 Repositories->New->Repository name->Public->Add a README file->Create repository
 Repositories->Repository name->Code->Clone
 
 2. Клонировать репозиторий JSON на локальный компьютер.
 - git clone (ссылка не репозиторий).

 3. Внутри локального JSON создать файл “new.json”. 
 
 - cd JSON (заходим в папку)
 - touch new.json (создаем файл)

 4. Добавить файл под гит.
 - git add new.json
 либо - git add .

 5. Закоммитить файл.
 - git commit -m "add 1 file"

 6. Отправить файл на внешний GitHub репозиторий.
 - git push

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 - vim new.json

{      "name": "Inna B.",
        "age": 28,
        "pet": "1 dog",
        "salary": 1000
 }

 8. Отправить изменения на внешний репозиторий.  
 - git commit -am "change file new.json"
 - git push

 9. Создать файл preferences.json
 - touch preferences.json
 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 - vim preferences.json
{      "favorite film": "The Silence of the Lambs",
        "favorite series": "Supernatural",
        "favorite food": "BBQ",
        "favorite season": "summer",
        "country": "Switzerland"
 }

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 - vim skills.json
 {       "skill 1": "GIT",
        "skill 2": "Postman",
        "skill 3": "Charles",
        "skill 4": "other"
 }

 12. Отправить сразу 2 файла на внешний репозиторий.
 - git add .
 - git commit -m "add 2 files"
 - git push

 13. На веб интерфейсе создать файл bug_report.json.
 - add file
 - create new file 
 - commit new file

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  - commit changes
 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 - edit this file
{
	"Identifier":1,
  	"Summary":"Site layout on the first page is not recommended with layout placement",
	"Descriprion":"Actual result and Expected result",
	"Actual result":"The layout of the site on the first page does not match the layout of the application. More than 5 pixel spacing",
	"Expected result":"The layout of the site on the first page matches the layout when overlaying. Run up to 5 pixels.",
	"Reproduced on":"Win 10",
	"Reproducibility":"always",
	"For more details see attachment":"https://www.screencast.com/t/hkQkQ8CeueY8",
	"Steps to reproduce":{"1":"Open website in Chrome",
	      		      "2":"Install and open PerfectPixel browser plugin",
              		      "3":"Drag the layout of the first page of the site in jpg format into the plugin window",
              		      "4":"Set the parameters in the plugin x=1, y=1, scale=0.24",
              		      "5":"Apply a layout layer to the layout of the site according to the edges of the main block",
              		      "6":"Hold down Shift + use arrow keys to change position by 10px"},
	"Severity":"minor",
	"Priority":"low"
} 
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 - commit changes
 
 17. Синхронизировать внешний и локальный репозиторий JSON
 - git pull
