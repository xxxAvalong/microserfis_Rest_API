This project is one of the possible implementations of the test assignment, which should demonstrate my skills in creating concise code and understanding the basic principles of programming.

In this project, I implemented the construction of a Python microservice, which will connect the console user interface to a remote API server, by means of https communication. The interface I created gives the user the ability to manage text posts, namely: create them, edit, delete and output to the console. The remote server is used as a source of posts and also to implement user validation when using some program functions. It also creates a .txt file with logs based on the inputs to the server.

This program consists of several Python modules, but I made sure there was no confusion and created one .pyz file based on several modules.

To run the program, double-click the file with the .pyz extension if you are running Windows. If your operating system is Linux, however, open the folder with the .pyz file at the command prompt and run the command: "python myapp.pyz" or "python3 myapp.pyz".


Also, in case of any problems with the .pyz file or any other unforeseen circumstances, I created another repository where I put the Python modules that I used to implement this project. If you want to use them as a program you just need to run the __main__.py script from the command line. Also for preloading the required libraries (requests and pyfiglet) in the repository added file: requirements.txt. Command line command to load the libraries: "python -m pip install -r requirements.txt".

It also goes without saying that you must have a Python interpreter installed in order to run the application in either variant. 
