# GITHUB_HW_2
GIT_HW_2
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

>Open GITHUB
Create new repository GITHUB_HW_2 
Copy SSH
Open GITBUSH
`$ git clone git@github.com:LiudmylaOleshko/GITHUB_HW_2.git`
`$ cd ./GITHUB_HW_2/`
`$git branch `
`* main`
`$ git branch Postman`
`$ git branch Jmeter`
`$ git branch Checklists`
`$ git branch BugReports`
`$ git branch SQL`
`$ git branch Charles`
`$ git branch MobileTesting`
`$ git branch`
`BugReports`
`Charles`
`Checklists`
`Jmeter`
`MobileTesting`
`Postman`
`SQL`
`* main`

2. Запушить все ветки на внешний репозиторий
>`$ git checkout Postman`
`$ git branch`
`BugReports`
`Charles`
`Checklists`
`Jmeter`
`MobileTesting`
`* Postman`
`SQL`
`main`
`$ git push origin Postman`

>`$ git checkout Jmeter`
`$ git branch`
`BugReports`
`Charles`
`Checklists`
`* Jmeter`
`MobileTesting`
`Postman`
`SQL`
`main`
`$ git push origin Jmeter`

>`$ git checkout Checklists`
`$ git branch`
`BugReports`
`Charles`
`* Checklists`
`Jmeter`
`MobileTesting`
`Postman`
`SQL`
`main`
`$ git push origin Checklists`

>`$ git checkout BugReports`
`$ git branch`
`* BugReports`
`Charles`
`Checklists`
`Jmeter`
`MobileTesting`
`Postman`
`SQL`
`main`
`$ git push origin BugReports`

>`$ git checkout SQL`
`$ git branch`
`BugReports`
`Charles`
`Checklists`
`Jmeter`
`MobileTesting`
`Postman`
`* SQL`
`main`
`$ git push origin SQL`

>`$ git checkout Charles`
`$ git branch`
`BugReports`
`* Charles`
`Checklists`
`Jmeter`
`MobileTesting`
`Postman`
`SQL`
`main`
`$ git push origin Charles`

>`$ git checkout MobileTesting`
`$ git branch`
`BugReports`
`Charles`
`Checklists`
`Jmeter`
`* MobileTesting`
`Postman`
`SQL`
`main`
`$ git push origin MobileTesting`

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
>`$ git checkout BugReports`
`$ vi bugreport.txt`
`I`
Bug-Report
Id: 	
Summary:
Description:
Pre-Conditions:
Steps:	1.
		2.
		3.
		4.
		5.
Expected Result:
ActualResult:	
Environment:
Severity:	
Priority:	
Type:
Attachment:
`ESC`
`:wq`
`Enter`

4. Запушить структуру багрепорта на внешний репозиторий
>`$ git add bugreport.txt`
`$ git commit -m "Add file bugreport.txt"`
`$ git push origin BugReports`

5. Вмержить ветку Bag Reports в Main
>`$ git checkout main`
`$ git merge BugReports`

6. Запушить main на внешний репозиторий.
>`$ git push origin main`

7. В ветке CheckLists набросать структуру чек листа.
`vi checklist.txt`
```
№   |Test Object	|Test description	|Status	|Enviroment	|
-------------------------------------------------------------------------
1   |			|			|	|		|
2   |			|			|	|		|
```

|№   |Test Object	|Test description	|Status	|Enviroment	|
|:---|:---|:---|:---|:---|
|1 |||||
|2|||||


8. Запушить структуру на внешний репозиторий
>`$ git add checklist.txt`
`$ git commit -m "Add file checklist.txt"`
`$ git push origin Checklists`

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
`Compare & pull request`
`Create pull request`
`Merge pull request`
`Confirm merge`

10. Синхронизировать Внешнюю и Локальную ветки Main
`$ git pull origin main`
