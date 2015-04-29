---
output:
  html_document:
    theme: united
---

New approch


I will follow git workflow describe in ["How I Manage Data Projects with RStudio and Git Part 2""][1] and linked there ["A successful git branching model"][2]

Shortly: we got two main paths: master & devel

Setup:

	# Basic setup
	git config credential.helper wincred # to remember password in RStudio/gitshell
	git config user.email ""
	git config user.name "refrence to place? say Marek@homeWin"
	git config [--global] merge.ff false
	??? push always with -all (configurable?)
	
	# devel bracnh
	git branch devel








[1]: http://christianlemp.com/blog/2014/02/13/How-I-Manage-Data-Projects-with-RStudio-and-Git-Part-2.html "How I Manage Data Projects with RStudio and Git Part 2"

[2]: http://nvie.com/posts/a-successful-git-branching-model/
