# Makefile-Builder

###Aim
To automate the process of building a pure C++ projects using a Makefile. This application generates the Makefile for a project. 

###Features
* Handles multi-level and single level projects
* Displays error message if the project has no main, multiple mains or no source files
* Once created, the user can easily edit the Makefile to meet his needs
* After creating the Makefile, the name of the execute on running ```make``` is the same as the file that contains the main functions

###Usage
* Copy the ```buildMakefile.sh``` in the root directory of the project
* Run the script using the following command -

```
sudo chmod +x buildMakefile
./buildMakefile
```

* A ```Makefile``` is created in the root directory
* Run ```make help``` for more assistance
