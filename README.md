### :large_orange_diamond: TXT
 _________________________________________________________________________________

 1. Создать внешний репозиторий c названием TXT.	      - [TXT](https://github.com/EvgeneyKEO/TXT.git)
 
 2. Клонировать репозиторий TXT на локальный компьютер	      
```
git clone https://github.com/EvgeneyKEO/TXT.git
```
 
 3. Внутри локального TXT создать файл “new.txt”.	    
 ```
 touch new.txt
 ```

 4. Добавить файл под гит.				    
 ```
 git add .
 ```

 5. Закоммитить файл.					      
```
git commit -m "add new file"
```

 6. Отправить файл на внешний GitHub репозиторий.	     
```
git push
```
 7. Отредактировать содержание файла “new.txt” - написать    
 информацию о себе (ФИО, возраст, количество домашних 
 животных, будущая желаемая зарплата). Всё написать в формате TXT. 				      
```
vim new.txt ---> input data ---> esc ---> enter ":wq"
```
 8. Отправить изменения на внешний репозиторий.	    
```
git commit -am "update file" && git push
```
 9. Создать файл preferences.txt
```
touch preferences.txt
```
 10. В файл preferences.txt добавить информацию о своих 
 предпочтениях (Любимый фильм, любимый сериал, любимая еда, 
 любимое время года, сторона которую хотели бы посетить) 
 в формате TXT.						     
```
vim preferences.txt ---> input data ---> esc ---> enter ":wq"
```
 11. Создать файл skills.txt добавить информацию о скиллах 
 которые будут изучены на курсе в формате TXT.		      
```
cat >> skills.txt ---> input data ---> ctrl + c
```
 12. Сделать коммит в одну строку.			      
```
git add . && git commit -m "add new file"
```
 13. Отправить сразу 2 файла на внешний репозиторий. [preferences.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/preferences.xml) [skills.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/skills.xml)	      
```
git push
```								
 14. На веб интерфейсе создать файл bug_report.txt.	      
```
Add file --> Create new file --> Name: bug_report.txt
```

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. [bug_report.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/bug_report.xml)				      
```
Commit New File 
```

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.	
```
Choose bug_report.txt --> Edit this file
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
Commit changes
```
 18. Синхронизировать внешний и локальный репозиторий TXT     
```
git pull
```
