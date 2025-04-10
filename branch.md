[<к содержанию>](README.md)
## git branch
![git-branch-512.webp](assets%2Fgit-branch-512.webp)

***Ветвление*** — это возможность работать над разными версиями проекта: вместо одного списка с упорядоченными коммитами история будет расходиться в определённых точках. Каждая ветвь содержит легковесный указатель <u>*HEAD*</u> на последний коммит, что позволяет без лишних затрат создать много веток. Ветка по умолчанию называется master, но лучше назвать её в соответствии с разрабатываемой в ней функциональностью.

Итак, есть общий указатель **HEAD и HEAD** для каждой ветки. Переключение между ветками предполагает только перемещение **HEAD в HEAD** соответствующей ветки.


Команды:

`git branch` *<имя ветки>* — создаёт новую ветку с HEAD, указывающим на HEAD. Если не передать аргумент <имя ветки>, то команда выведет список всех локальных веток;

`git checkout` *<имя ветки>* — переключается на эту ветку. Можно передать опцию -b, чтобы создать новую ветку перед переключением;

`git branch` -d *<имя ветки>* — удаляет ветку.
***
[вперед](GitHub.md)