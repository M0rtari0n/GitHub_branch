1. На локальном репозитории сделать ветки для:
- Postman - "git branch Postman"
- Jmeter - "git branch Jmeter"
- CheckLists ================================================================ "git branch CheckList"
- Bug_Report ================================================================ "git branch Bug_report"
- SQL ======================================================================= "git branch SQL"
- Charles =================================================================== "git branch Charles"
- Mobile_testing ============================================================ "git branch Mobile_testing"

2. Запушить все ветки на внешний репозиторий ================================ "git push --all"

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта = "> bug_report_structere.txt"
									      "vim bug_report_structere.txt"
									      "cat bug_report_structere.txt"

									       Bug_report_texture:

									       Summary:
									       Project:
									       Component:
									       Version:
									       Severity:
									       Priority:
									       Status:
									       Author:
									       Assigned to:
									       Description:
									       Attachment:

4. Запушить структуру багрепорта на внешний репозиторий ===================== "git add ."
									      "git commit -am "change bug_report_texture.txt""
									      "git push -u origin bug_report"

5. Вмержить ветку Bag Reports в Main ======================================== "git checkout main"
									      "git merge bug_report"

6. Запушить main на внешний репозиторий. ==================================== "git push"

7. В ветке CheckLists набросать структуру чек листа. ========================="git checkout checklist"
									      "> checklist_structure.txt"
									      "vim checklist_structure.txt"
									      "cat checklist_structure.txt"

									      Structure:

									      Action:
									      Expected Result:
									      Test Result:



8. Запушить структуру на внешний репозиторий ================================ "git add ."
									      "git commit -am "change_checklist_structure"
									      "git push -u origin checklist"

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main ====== "compare & pull request => create pull request => merge pull request => confirm merge"

10. Синхронизировать Внешнюю и Локальную ветки Main ========================= "git pull"
