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











🔹 File and Directory Management
Command	Description
ls	List directory contents
cd [dir]	Change directory
pwd	Show current directory
mkdir [dir]	Create new directory
rm [file]	Remove file
rm -r [dir]	Remove directory recursively
cp [src] [dest]	Copy file or directory
mv [src] [dest]	Move or rename file/directory
touch [file]	Create a new empty file
find [dir] -name [file]	Search for files

🔹 File Viewing and Editing
Command	Description
cat [file]	View file contents
less [file]	View file with navigation
head [file]	Show beginning of file
tail [file]	Show end of file
nano [file]	Simple command-line text editor
vim [file]	Powerful text editor

🔹 Permissions and Ownership
Command	Description
x 
chown [user]:[group] [file]	Change file owner

🔹 Process and System Management
Command	Description
ps aux	List all running processes
top	Real-time process monitoring
kill [PID]	Terminate process by PID
htop	Interactive process viewer (if installed)
df -h	Show disk space usage
du -sh [dir]	Show size of a directory
free -h	Show memory usage
uptime	Show system uptime and load

🔹 Networking
Command	Description
ping [host]	Test network connection
ifconfig or ip a	Show IP address and interfaces
netstat -tuln	Show active ports (deprecated, use ss)
ss -tuln	Show listening sockets
curl [url]	Transfer data from/to server
wget [url]	Download files

🔹 Package Management (Ubuntu/Debian)
Command	Description
sudo apt update	Update package list
sudo apt upgrade	Upgrade installed packages
sudo apt install [pkg]	Install a package
sudo apt remove [pkg]	Remove a package




 
