# Linux-comments-
ls
	list the directories and files in a location
ls folder_name
	list the files in the folder
ll
	list the files and folders with more details
cd folder_name
	switches to the given folder
cd .
	stays in the current directory
cd ..
	switch to the parent directory
cd 
	moves to the home directory
mkdir folder_name
	creates a directory
mkdir -p folder_name/folder_name
	creates a folder along with its parent directory
	if there is no parent directory
rmdir folder_name
rm folder_name
	removes the directory if only it is empty
rm -R folder_name
	removes recursively all the sub folders and files
touch file_name
	creates an 0 byte empty file
echo 'some content' > file_name
	overwrites the file with given content
echo 'some content' >> file_name
	appends the file with given content
cat file_name
	shows the content of the file
less file_name
	allows scrolling through the long content
	Shift+G	=> moves to the end of the content
	\q => exits the editor
nano file_name
	opens/creates a file
	a simple editor for working with files in CUI
	Ctrl+O and the given the filename to save the file
	Ctrl+X to exit the editor
