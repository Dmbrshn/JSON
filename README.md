# JSON
 1.  Создать внешний репозиторий c названием JSON: 
 
    На GitHub выбрать вкладку "Repositories", нажать "New", в окне "Repository name" написать "JSON", поставить галочку напротив "Add a README file", нажать "Create repository"
 2.  Клонировать репозиторий JSON на локальный компьютер: 
   
    git clone https://github.com/Dmbrshn/JSON.git
 3.  Внутри локального JSON создать файл "new.json": 
   
    touch new.json
 4.  Добавить файл под гит: 
    
    git add new.json
 5.  Закоммитить файл: 
    
    git commit -m "new file"
 6.  Отправить файл на внешний GitHub репозиторий: 
    
    git push
 7.  Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON: 
    
    vim new.json , i , набираем нужный текст, :wq  
 8.  Отправить изменения на внешний репозиторий:
    
    git add new.json && git commit -m "Edit file" && git push
 9.  Создать файл preferences.json:
    
    touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
    
    vim preferences.json , i , набираем нужный текст, :wq 
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:
    
    touch skills.json && vim skills.json , i , набираем нужный текст, :wq 
 12. Отправить сразу 2 файла на внешний репозиторий:
    
    git add . && git commit -m "preferences and skills" && git push
 13. На веб интерфейсе создать файл bug_report.json:
    
    В Репозитории "JSON" нажать "Add file" , выбрать "Create new file" , в поле "Name" написать "bug_report.json" 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    
    Нажать "Commit new file"
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:
    
    В Репозитории "JSON" выбирать файл "bug_report.json" , нажать на иконку "карандаш" , набираем текс 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
 
    Нажать "Commit changes"
 17. Синхронизировать внешний и локальный репозиторий JSON:
 
    git pull
