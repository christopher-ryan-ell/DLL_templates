1. Clone repository from GitHub
2. On GitHub settings publish as github pages (make sure correct branch is published)
3. Save template.xml with new name (e.g., catullus.xml)
4. make your file
5. modify line 40 of template.html to point to the correct xml file name (eg, catullus.xml)
6. add necessary files and commit necessary files to local repository
	git add whatever_file.xml \\NB: even files that were a part of the initial checkout need to be added to the queu of things to commit
	\\ in this example, I created a new file (catullus.xml) and modified an existing on (catullus.html). Both need to be added before the commit
	git commit -m "change comments"
7. push to github
	git push
8. view website 
	https://christopher-ryan-ell.github.io/training/catullus.html
	the catullus.html file (presumably rename for other projects) is what will render in web browser using the css and js libraries
	catullus.html line 40 points to the appropriate xml file to render
	these are the only two files to screw with for other projects; could just create a separate repository, add everything in the training directory, and then rename and edit these two files
	critical material does not display by default; must click on section in ToC in order to display critical material

Note that git is not necessary for testing
the template.html can be opened directly from the file system by firefox for a more instantaneous check on how things are working
for reasons unknown, chrome does not like this (and neither does IE or Edge)