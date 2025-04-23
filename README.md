# 19CS416-CS-Ex-3-Linux-Commands
# NAME = RATHISH KUMAR C
# REG NO = 21222100043

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

# 19CS416-CS-Ex-3b-Kali linux
## Procedure:
1. Go to the Website: Visit the official site at https://www.kali.org.

2. Click “Download”: On the homepage, click the “Download” button or go to https://www.kali.org/get-kali/.

3. Choose Version: Select the version you need (Installer, Live, or Virtual Machine), and choose 64-bit or 32-bit.

4. Download ISO/VM Image: Click to download the ISO file or pre-built VirtualBox/Vmware image.

5. Verify & Save: (Optional but recommended) Use the SHA256 hash to verify the file, then save it to your system.


## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![427555018-76dc10ce-a94f-4aee-8f9f-adcc903b5050](https://github.com/user-attachments/assets/08e910a1-293d-4acb-88ef-44049604437f)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![427555536-92e82e0c-8b68-47bc-bd36-6302eef18fe1](https://github.com/user-attachments/assets/7da7918b-78fa-4bc4-a535-ba2f3e7f7919)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![427555788-a07bbcfe-8b5c-4054-9728-bcb375711b13](https://github.com/user-attachments/assets/818e8fe8-1344-4366-aebb-c9536c4c262c)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![427555941-39e68300-cdf3-44b8-9c70-49e0ed80daed](https://github.com/user-attachments/assets/055b94cc-1d37-4cb0-b4fc-84e091e63bd1)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![427556261-0b6dfbda-a084-43ab-a3b9-564e89f8fe2a](https://github.com/user-attachments/assets/b7f87ccc-fd79-4679-a659-0c9d5087cc19)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output
![427556469-5308059e-c8dc-4374-ba23-e151ed62c6ff](https://github.com/user-attachments/assets/d681c5b6-45cf-4b12-bf18-aa30ff73d74d)

:**

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output 
![427556965-03783054-48fe-4af5-96f8-b9b178671f03](https://github.com/user-attachments/assets/10f1fc72-b422-4d2c-8cc8-56deb7a82259)
ut:**

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![427557185-f6122908-5022-41d5-8b5e-92bcbc93217e](https://github.com/user-attachments/assets/96f3010a-ab97-4b22-857a-8fbbc1332981)
### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:
![427557863-08db1911-3afc-48cf-8230-8e44068bbc43](https://github.com/user-attachments/assets/4354db03-5d97-4f4f-a0f7-d41e419fe68f)
**

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:
![427558050-414fa66f-dacc-4ce7-bf63-787bab95011f](https://github.com/user-attachments/assets/c2c02321-d4bc-4167-8e7f-399a4b0231cf)
**

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output
![427558265-c168d024-e903-4499-b898-4271c94c3b7a](https://github.com/user-attachments/assets/b7098325-f196-4521-9a48-cb8688bc2fd7)
put:**

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![427558265-c168d024-e903-4499-b898-4271c94c3b7a](https://github.com/user-attachments/assets/4d20d704-f0dc-459c-9852-1cee6fbdb672)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![427559133-6066c8b7-957a-410d-a263-8bc1d6a73260](https://github.com/user-attachments/assets/7e3a98e4-e343-4876-9043-78453aa0761a)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![427559481-4dca4667-6b53-4c51-8cec-5b066b73dacc](https://github.com/user-attachments/assets/7f67a36c-0a14-4451-9a32-2d3818c8521c)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![427589521-d9bd5603-b7ac-405b-8167-40d01e8aeceb](https://github.com/user-attachments/assets/15c627f3-8d9d-43fb-a7e5-4d3b35dba852)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![427589685-e16f7228-596c-4940-a73a-0049e484964b](https://github.com/user-attachments/assets/a5d4222a-0fe3-4466-beab-9f997ccdd056)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![427560793-d9bca3d1-65d2-478a-9fd6-949b225f7550](https://github.com/user-attachments/assets/145be69e-00c3-425c-980e-95e0b7169211)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![427561184-d69d155c-369f-4b9c-bac2-75ad270ee4cf](https://github.com/user-attachments/assets/9f1d6f92-46e7-4504-8fe9-df7dff743942)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![427561752-8a825258-4673-46f7-83e5-47290977bc73](https://github.com/user-attachments/assets/b34d012a-fc6d-4380-beb7-0795c50c42d7)
*

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output
![427562064-8b41db02-b3af-4055-932b-7ca1851c46e2](https://github.com/user-attachments/assets/4deeb987-fc39-4fe9-8c39-018a7e69264f)
:**

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![427562337-9d51f888-f806-49db-9a63-3bf7c3d43643](https://github.com/user-attachments/assets/054f8bab-1e08-47c6-b202-891b325ebbeb)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![427562590-d1086111-de23-4328-b41a-65933b77edbe](https://github.com/user-attachments/assets/ead16232-a880-431f-8c79-eb3048c32748)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**![427562890-5fe4509f-5f8d-4ebb-9db8-bf5d86836c96](https://github.com/user-attachments/assets/780edc21-831f-4bd5-8967-62d7820d3720)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![427589856-ead26219-dc40-4ae9-ac3b-831aa8d4364e](https://github.com/user-attachments/assets/c9c33a55-ee78-40ca-af6e-94724e2edac2)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output**
![427563388-f03383cc-f03b-4a6c-8a9d-e37363a1ed4a](https://github.com/user-attachments/assets/a923dc29-2a2e-475a-a23d-eccbb6574e9f)
t:**

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![427563853-16492388-8cc1-4dbe-9e68-085b6c794fa1](https://github.com/user-attachments/assets/74cd05dd-0029-472f-a7d8-6fb78fd3d5c1)

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![427564107-a097b498-efbc-484b-8f20-7c1335635f6c](https://github.com/user-attachments/assets/c26f979a-4d8b-41a5-8b7d-acc217f0f195)

## Result
Successfully performed the series of Linux commands as specified.
