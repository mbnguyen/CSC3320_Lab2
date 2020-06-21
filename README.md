Name: Minh Binh Nguyen
PantherID: 002-46-4288
-------------------------------------
	README.md

In this assignment, I did:
1. Make a new directory (folder) named "Submissions" (Pic 1)
	mkdir Submissions
2. Change the permission to the Submissions folder so that the other students cannot read, write and execute (Pic 1)
	chmod -R o-rwx Submissions
3. Change the group to cumoja1@gsuad.gsu.edu so that I can give this user the permissions (Pic 1)
	chgrp -R cumoja1@gsuad.gsu.edu Submissions
4. Change the group's permission so that cumoja1@gsuad.gsu.edu can read and execute this folder (Pic 2)
	chmod -R g=rx Submissions
5. Navigate to the folder 3320 in the cumoja1 to find the document (Pic 3)
	cd ../cumoja1/
6. Copy the document to my home directory (Pic 3)
	cp The\ Hunger\ Games.txt ~
7. Move the document to the Submissions folder (Pic 3)
	mv The\ Hunger\ Games.txt Submissions
8. Make sure to set the right permissions to the file (Pic 4)
	chmod -R g=rx,o-rwx The\ Hunger\ Games.txt
9. Use Vi editor to view and edit the file (Pic 5)
	vi The\ Hunger\ Games.txt
10. Search the entire file for "Gale" and replace them with my name "Minh" (Pic 5 and Pic 6)
	:%s/Gale/Minh/g
11. Rename the document to "My Hunger Games.txt" (Pic 7)
	mv The\ Hunger\ Games.txt My\ Hunger\ Games.txt
12. Compress the Submissions folder to the MinhNguyenLab2.tar (Pic 8)
	tar cf MinhNguyenLab2.tar Submissions

