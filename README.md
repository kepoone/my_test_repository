git init . (указываем рабочую область в текущей директории)
git add ./file1.txt (добавить в git file1.txt)
git status (узнать статус)
git commit -m "My initial commit? this is Version1.0" (сделать снимок)
git checkout -- file.txt (отменяет изменения в последнем файле)
git log (история изменений)
git log -1 (последнее изменение)
git log -1 -p (последнее изменение детально)
git diff --staged (показывает какие изменения будут внесены перед коммитом)
git clone http://.../.git (делает копию репозитория с гитхаб)
git push origin (загрузка в github)


.gitignore (создаем файл для игнорирования git'ом некоторых файлов, прописываем в него что игнорировать)
*.log (например все логи)


 echo "HelloGit" > file.txt 		git add file.txt		git commit -m "Version1"		git push
       	 Untracked			     Staged				Copy in 			 Copy in
									    Local Reposytory		     Remote Repository

