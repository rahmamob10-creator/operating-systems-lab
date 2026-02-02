# Lab 01 – Directory and File Management Commands (Windows)

## Objective
To understand basic directory and file management commands using the Windows Command Prompt.

---

## 1. Creating Directories (md)

### Single Folder
md c:\new
**Description:** Creates a new folder named `new` in the root of the C: drive.  
The backslash `\` indicates the root directory.

### Multiple Folders/Subdirectories
md c:\new\data
md c:\new\programs
md c:\new\utility
md c:\new\data\stuff
md c:\new\data\letters
**Description:** Creates multiple directories and subdirectories at once.

---

## 2. Changing Directories (cd)

### Commands
cd foldername
cd..
cd\
**Description:**  
- `cd` → move into a specified directory  
- `cd..` → move one level up (parent directory)  
- `cd\` → move directly to the root directory
- commands I perfomed
- https://github.com/rahmamob10-creator/operating-systems-lab/blob/e2ad756cca674fe46ec2d18351af6a59cdfd7133/window%20commands%20image.1.png

---

## 3. Creating Text Files (copy con)

### Command
copy con c:\new\utility\hello.txt
**Description:** Creates an ASCII text file. Type your text, press **Ctrl + Z** and **Enter** to save.

### Additional Files
- `goodbye.txt`  
- `dejavu.txt`  

Can also be created using Notepad.

---

## 4. Display File Contents (type)

### Command
type c:\new\utility\dejavu.txt
**Description:** Displays the contents of a file in the command prompt.

---

## 5. Clearing the Screen (cls)

### Command
cls
**Description:** Clears the command prompt screen.

---

## 6. Listing Directory Contents (dir)

### Command
dir c:\new
**Description:** Lists the contents of the `c:\new` directory.

### Include Subdirectories
dir c:\new /s
**Description:** Lists all files in subdirectories as well.

---

## 7. Copying Files (copy)

### Command
copy c:\new\utility\hello.txt c:\new\data\stuff\hello.txt
**Description:** Copies `hello.txt` from the utility folder to the stuff folder.

### Verify
dir c:\new\data\stuff

---

## 8. Comparing Files (fc)

### Command
fc c:\new\utility\hello.txt c:\new\data\stuff\hello.txt
**Description:** Compares two files and shows differences if any.
commands I performed
https://github.com/rahmamob10-creator/operating-systems-lab/blob/e2ad756cca674fe46ec2d18351af6a59cdfd7133/windowcommands%20image.2.png

---

## 9. Moving Files (move)

### Command
move c:\new\data\stuff\hello.txt c:\new\data
**Description:** Moves `hello.txt` from the stuff directory to the data directory.

---

## 10. Removing Directories (rd)

### Command
rd c:\new\utility
**Description:** Deletes the utility directory.

---

## 11. Renaming Files (ren)

### Command
ren c:\new\utility\hello.txt aloha.txt
**Description:** Renames `hello.txt` to `aloha.txt`.

---

## 12. Deleting Files (del)

### Command
del c:\new\data\hello.txt
**Description:** Deletes the file from the data directory.

---

## 13. Displaying Directory Tree (tree)

### Command
tree /f
*description:** Shows the folder tree including all files. `/f` includes files in the display.

commands I performed
https://github.com/rahmamob10-creator/operating-systems-lab/blob/e2ad756cca674fe46ec2d18351af6a59cdfd7133/windowcommand%20image.3.png


