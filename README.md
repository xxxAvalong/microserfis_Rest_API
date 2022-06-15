This project is one of the possible implementations of the test assignment, which should demonstrate my skills in creating concise code and understanding of basic programming principles.

In this project, I implemented the construction of Python microservice, which will connect the console user interface to a remote API server, through https communication. The interface I built gives the user the ability to manage text posts, namely: create them, edit, delete and output to the console. The remote server is used as a source of posts and also for user validation when using some functions of the program. The program also creates a .txt file with logs based on the data coming to the server.

This program consists of several Python modules, but I made sure there was no confusion and created one .pyz file based on several modules.

To run the program, double-click the file with the .pyz extension if you're running on Windows. If your operating system is Linux, however, open the folder with the .pyz file at the command prompt and run the command: "python myapp.pyz" or "python3 myapp.pyz".

You will also find documentation for the modules I created in the docs folder. To view it you need to download all the files in one folder and run one of the .html files in your browser.


Also, just in case there are problems with the .pyz file or other unforeseen circumstances, I created another folder where I put the Python modules that I used to implement this project. If you want to use them as a program, you just have to run the __main__.py script from the command line. Also, to preload the required libraries (requests and pyfiglet), a file has been added to the repository: requirements.txt. The command line command to load the libraries is "python -m pip install -r requirements.txt".

It goes without saying that you must have the Python interpreter installed to run the application in either variant. 
