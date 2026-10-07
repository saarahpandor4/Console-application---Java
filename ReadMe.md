- Recursive Directory Listing

This exercise demonstrates how to use recursion in Java to list files and directories.

# What I Learned:

- How to use the File class.
- How to check if something is a file or directory.
- How recursion works in Java.
- How to compile and run a Java program.
- Program Structure

# The method:

1. Lists the contents of the current directory.
2. Checks each item to see whether it is a file or directory.
3. Prints the absolute path if it is a file.
4. Calls itself again if it is a directory.

- How to Compile:

From the 'consoleapp_proj' directory:

' javac -d classes src/DirectoryRecursiveList.java '

- How to Run:

'java DirectoryRecursiveList'

When prompted, enter a directory path. For example:

' text . '

The '.' represents the current directory.

- Example

Enter 1 and then enter a directory path, such as '.' to list the current directory.

# Recursion

The program calls directoryList() again whenever it finds a subdirectory, allowing it to search through all folders and files.
