# Lab Report 3

## Command: find
Find is a command that can be used to search for files or directories in a given path.
Here are 4 different options that you can use with find with 2 examples for each:


### Option 1: -type
This option allows you to look for files and directories of a particular type. The type can be f for files, d for directories, or l for symbolic links.

This would be useful if you want to filter out all the files or directories from a certain location. For example, if you have a folder containing several directories and two files, and you want to access just those two files, you can use `-type f` to filter out just the two files needed. This will save the user the trouble from having to manually search just for the files amongst the several other directories.

Example 1: Searching for all directories in written_2

![image](https://user-images.githubusercontent.com/61783850/218347703-4bc75815-63f9-489c-b12f-882693eca0ec.png)

Example 2: Searching for all files in written_2/non-fiction/OUP/Kauffman

![image](https://user-images.githubusercontent.com/61783850/218347836-36a99545-e393-45f9-8b9f-c528c20dac9b.png)

Source: [OpenAI (2023). ChatGPT](https://openai.com/products/gpt-3/) & 
[https://linux.die.net/man/1/find](https://linux.die.net/man/1/find)


### Option 2: -name
This option allows you to find a certain file or directory with a specific name.

If you want to find one specific file or directory from several other files and directories from a location, you can use `-name` to find it instead of having to manually look through hundreds of other files and directories. This makes things easier and will save the user a lot of time and effort.

Example 1: Searching for a file named WhatToHawaii.txt inside written_2

![image](https://user-images.githubusercontent.com/61783850/218347031-b51b6b68-a707-4374-bf15-a4ef2337e6ce.png)

Example 2: Searching for the directory named Kaufman inside written_2

![image](https://user-images.githubusercontent.com/61783850/218347166-02d397d0-d248-4fe3-86b7-71637bdb566c.png)

Source: [OpenAI (2023). ChatGPT](https://openai.com/products/gpt-3/) & 
[https://linux.die.net/man/1/find](https://linux.die.net/man/1/find)


### Option 3: -exec
This option allows you to execute a specified command on each file or directory that matches the search pattern.

This can be useful in several ways. One way as demonstrated with example 1 is if you want to see how much storage is being used up by the files in a directory. This can be useful to manage your system's disk usage. This command is not limited to just the two examples, and can be used in several other useful ways.

Example 1: Displaying the file sizes of all files in the written_2/non-fiction/OUP/Kauffman directory.

![image](https://user-images.githubusercontent.com/61783850/218348463-047027a9-5805-4c34-b68b-d0123eaccd84.png)

Example 2: Displaying the number of lines in all ".txt" files in the written_2/non-fiction/OUP/Kauffman directory.

![image](https://user-images.githubusercontent.com/61783850/218348579-74067e9e-f015-4807-8edd-dcb5d37207b1.png)

Source: [OpenAI (2023). ChatGPT](https://openai.com/products/gpt-3/) & 
[https://linux.die.net/man/1/find](https://linux.die.net/man/1/find)


### Option 4: -size
This option allows you to filter out files that are greater than or less than the specified filze size.

This can be useful for managing storage. If your disk is running out of space and you have to clear some large files, you can use this command option to filter out large files so that it's easy to delete.

Example 1: Displaying all files in written_2 that are greater than 100 kilobytes.

![image](https://user-images.githubusercontent.com/61783850/218348934-06142710-eaa4-400c-9de6-830b15678556.png)

Example 2: Displaying all files in written_2 that are less than 3 kilobytes.

![image](https://user-images.githubusercontent.com/61783850/218349013-7a96f4c1-7707-4502-b471-4aa6053e405d.png)

Source: [OpenAI (2023). ChatGPT](https://openai.com/products/gpt-3/) & 
[https://linux.die.net/man/1/find](https://linux.die.net/man/1/find)
