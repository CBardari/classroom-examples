-_**ls**_
  -Linux Terminal Command
  -Prints the files and folders in the current directory
  -The following strings can be added to the command for certain effects    
    -"-a"  : Show Hidden Files
    -"-l"  : Show large form of files / more information about files (creation date, edit date, file type)
    -"-la" : Combines the effect of both -a and -l
  -"ls <File Directory>" can be used to show the files of a specific directory

-***mkdir*** (make directory)
  -Linux Terminal Command
  -Creates a directory within the current directory
  -"mkdir <Name of directory you want to create>" 
    -example: "mkdir Directory_2" = this command will create a directory called "Directory_2" in the current directory

-_**cd**_ (change directory)
  -Linux Terminal Command
  -Changes the file directory that you are in
  -"cd .." can be used to return to the parents directory of the current directory
    -"cd ../../.." returns to third previous directory (../../ can return to the parent directory of the parent directory of the current directory)
  -"cd <name of parent directory>" will not go back to the parent directory, ".." must be used to go to the parent directory
  -cd can change multiple directories/ can change directory through a directory, for example: "cd directory1/sub_directory1/subdirectory_2"
  -"cd" alone will change the current directory to the home directory
    -"cd ~" will produce the same result

-***touch***
  -Linux Terminal Command
  -Creates a file within the current directory
  -ex.: "touch test_file.txt" -> creates a text file called "test_file"

-***rm***
-Linux Terminal Command
-deletes files
-"rm copy_file.txt" -> deletes a file called "copy_file"
-doesn't get sent to trash can // instantly deleted
-file must be in the current directory
-"rm -R CopyDir" -> deletes the directory "CopyDir"
-"rm -rf" forces a deletion

-***cp***
-copies (and pastes) a file or a directory
-"cp test_file.txt copy_file.txt" -> copies a file caled "test_file" and creates a file called "copy_file" with the same contents
-"cp -R TestDir/CopyDir" -> copies and pastes the contents inside the directory "TestDir" into the directory "CopyDir"

-***mv***
-Linux Terminal Command
-used to move and rename files (or both)
-"mv test_file.txt orig_file.txt" -> changes the name of a file called "test_file" to "orig_file"
-"mv orig_file.txt SubDir1" -> moves a file called "orig_file" to a directory called "SubDir1" without renaming it
-"mv orig_file.txt SubDir1/test_file.txt" -> moves a file called "orig_file" to a folder called "SubDir1" and renames it to "test_file"
-"mv TestDir OrigDir" -> renames the directory "TestDir" to "OrigDir"
-"mv OrigDir/CopyDir" -> moves the directory "OrigDir" into a directory called "CopyDir"
-"mv OrigDir/ParentDir/TestDir" ->moves the directory "OrigDir" into the directory "ParentDir" and renames "OrigDir" into "TestDir"

-***cat*** (concacate(combine))
-"cat /Directory1/File.txt" -> Displays the contents of the file "File.txt" in the directory "Directory1"
-"cat File1.txt File2.txt File3.txt" -> Displays the contents of all these files (on different lines)
-"cat >File1.txt" -> Creates a file called "File1.txt"
-"cat -n File1.txt" -> outputs the content of the file with numbered lines
-"cat File1.txt File2.txt" -> Copies the content of File1 into File2
-"cat File1.txt>>File2.txt" -> Prints out the contents of file1 and file2 appended (together)
-"tac File1.txt" -> Prints out the content of File1 in reverse order
