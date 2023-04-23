<div align="center">

# GitHub. HW_2

</div>
  
1. На локальном репозитории сделать ветки для:  
- Postman `git branch Postman`
- Jmeter `git branch Jmeter`
- CheckLists `git branch CheckLists`
- Bug Reports `git branch BugReports`
- SQL `git branch SQL`
- Charles `git branch Charles`
- Mobile testing `git branch MobileTesting`

2. Запушить все ветки на внешний репозиторий  
`git add .`  
`git commit 'new branch'`  
`git checkot main`  
`git push -u origin 'Postman' 'Jmeter' 'CheckLists' 'BugReports' 'SQL' 'Charles' 'MobileTesting'`  

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта  
`git checkout BugReports`  
`vim BugReports.txt`  
```
ID: BR-5,
Title: What? Where? When?,
Severity: Medium,
Priority: High,
Precondition: Preparation steps,
Environment: Devices,
STR: Steps to reproduce,
ER: Expected result,
AR: Actual Result,
Attachment: link
```

4. Запушить структуру багрепорта на внешний репозиторий  
`git add .`  
`git commit -m 'BugReports'`  
`git push`  

5. Вмержить ветку Bug Reports в Main  
`git checkout main`  
`git merge BugReports`

6. Запушить main на внешний репозиторий.  
`git add .`  
`git commit -m 'merge BugReports'`  
`git push`  

7. В ветке CheckLists набросать структуру чек листа.  
`git checkout CheckLists`  
`vim CheckLists.txt`  
```
1 - ID
2 - Title
3 - Status
4 - Link
```

8. Запушить структуру на внешний репозиторий  
`git add .`  
`git commit 'check'`  
`git push`  

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
Перейти на `https://github.com/mranolegprivate/HW_2_Branch` нажать `Compare&pull requset`

10. Синхронизировать Внешнюю и Локальную ветки Main  
`git checkout main`  
`git fetch`  
`git pull`
