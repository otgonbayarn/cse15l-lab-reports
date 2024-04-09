For ```cd``` commands:

1. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175657.png?raw=true)

Absolute path was cd /c/Users/nyamb/lecture1 before the command.

No output was shown, and since it was used without arguments it returned to home directory.

There was no output, and it was not an error.

2. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175706.png?raw=true)

Absolute path was /c/Users/nyamb before the command.

The command changed my current directery to my specified directory, /c/Users/nyamb/lecture1/messages

There was no output, and it was not an error.

3. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175718.png?raw=true)

Absolute path was /c/Users/nyamb/lecture1/messages before the command.

The output was "Not a directory" , because command cd is for changing directories not files.

There was an error, command cd expects directory but file was provided instead.


For ls commands:

1. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175807.png?raw=true)

Absolute path was /c/Users/nyamb before the command.

The ls command was used without arguments, so it listed the files and folders of the current directory /c/Users/nyamb.

The output provided the files and folders of current directory, so there was no error.

2. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175817.png?raw=true)

Absolute path was /c/Users/nyamb before the command.

The ls command was used with argument $ ls /c/Users/nyamb/lecture1/messages, so it listed the files and folders of the that directory.

The output provided the files and folders of current directory, so there was no error.

3. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20190118.png?raw=true)

Absolute path was /c/Users/nyamb/lecture1/messages before the command.

The ls command was used with argument $ ls en-us.txt, and gave output "No such file or directory". This was due to command ls expected directory as an argument, but a file was provided instead.

The output provided error: No such file or directory. Because file was provided in the argument instead of directory.

For cat commands:

1. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20175913.png?raw=true)

Absolute path was /c/Users/nyamb/lecture1/messages before the command.

The cat is used to print contents of files given by the paths, but this there was no argument/path was given so there is no output provided.

There was no output, so thre is no error.

2. ![Image]( https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20180159.png?raw=true)

Absolute path was /c/Users/nyamb/lecture1/messages before the command.

The cat is used to print contents of files given by the paths, but we provided directory instead of files. Therefore the output "cat: /c/Users/nyamb/lecture1/messages: Is a directory" was given.

There is an error "cat: /c/Users/nyamb/lecture1/messages: Is a directory", because the command expects a file as an argument, but a directory was provided instead.

3. ![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/main/Screenshot%202024-04-08%20180211.png?raw=true)

Absolute path was /c/Users/nyamb/lecture1/messages before the command.

The cat printed the content of the current given files of path, which is "Hello world!".

There is no error as it provided the contents of the given file.
