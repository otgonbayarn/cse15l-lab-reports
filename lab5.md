Student:

Hello CS15L, My code compiles and runs, but it doesn't recognize the file. I am gonna attach the code and the terminal output:

![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/aa65299ca6c89a3a63ac73aebbf41954f6cb237c/Screenshot%202024-06-05%20221325.png?raw=true)

![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/b2494bb79bb2dd9bd4548be32b735fa0b69b0282/Screenshot%202024-06-05%20225409.png?raw=true)

TA:

It looks like the program might be running from a different directory. Make sure you are running the program from the directory where the file is located. You can also try using a relative path like ./testfile.txt to ensure it checks the current directory.
Try running with the following code: 

![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/447b81d35562ec71c44a6354aaaf93aa5d86e48b/Screenshot%202024-06-05%20222527.png?raw=true)

Student:

Thank you for the help, I ran the program again with the relative path, and it worked! The file was recognized, and the output is now correct.

![Image](https://github.com/otgonbayarn/cse15l-lab-reports/blob/71c9dd5664c7fed9a62bb0110913c91c9375979c/Screenshot%202024-06-05%20223137.png?raw=true)


File and directory structure:
```
    user/lab7
    ├── Code.java
    └── testfile.txt
    ``` 
```

Contents of each file: These are provided by the screenshots


The full command line (or lines) you ran to trigger the bug:

 ```bash
    javac Code.java
    java Code testfile.txt
    ```
```

Bug FIX:

Used the relative to ensure the file is checked in the correct directory:
    ```bash
    java Code ./testfile.txt
    ```

Part 2: Reflection

In the second half of this quarter, I learned a lot about debugging techniques and file handling in Java. Debugging with jdb has provided me with more precise control over the debugging process compared to traditional print statements. Also, working entirely in the terminal for file handling and debugging enhanced my command line skills and reduced reliance on tools like VS Code. The lab experiences has significantly improved my debugging skills and my ability to troubleshoot complex issues in Java programs.

