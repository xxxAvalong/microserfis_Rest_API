This project is one of the possible implementations of the test assignment, which should demonstrate my skills in creating concise code and understanding of basic programming principles.

In this project, I implemented the construction of Python microservice, which will connect the console user interface to a remote API server, through https communication. The interface I built gives the user the ability to manage text posts, namely: create them, edit, delete and output to the console. The remote server is used as a source of posts and also for user validation when using some functions of the program. The program also creates a .txt file with logs based on the data coming to the server.

This program consists of several Python modules, but I took care to avoid confusion and created one .pyz file based on several modules.

To run the program, double-click the file with the .pyz extension if you're running on Windows. If your operating system is Linux, however, open the folder with the .pyz file at the command prompt and run the command: "python myapp.pyz" or "python3 myapp.pyz".

After starting the program you will see a login confirmation window, you have to press "e" to continue. You will then be able to select the interaction mode. 
1 - Create a post and save it locally in the folder with the program(post id will be used as a .txt file name), for this action you need to pass validation and the userId you used will also be saved in the post. The first post will get the id 101, so that in case of synchronization with the server there were no conflicts, the next 102 and so on.   After validation the logs.txt file will appear with userId, time, date and login purpose.
2- Show post. In this case there are two modes by userId and id. In the first case, the posts will be searched in the system. The content of each post in the system ( application folder ) will be checked for the userId you are looking for with the parser. As a result, you will be shown all the posts with matching userId inside. The second mode will search the post by its id not only in the system but also on the server if the post is not found in the system. As the post in the system is understood .txt file which name consists of numbers.
3,4 - These modes are very similar so I will not separate them as I did not do it when I was making the application. These two modes use the same function.
The target post is searched in the system for deletion/editing by its id. These modes also suppose the possibility to activate validation, the function used can do this, but I didn't use this because the task does not require validation for these actions. Also, if you edit a post without validation, the post will have the same userId. If you enable (this can be done in the wrapped function in the source code) validation, the edited post will have the userId used for validation.
Also, to navigate to the exit you have to press "q".

In the docs folder you will also find the documentation for the modules I created. To view it, you need to download all the files in the same folder and run one of the .html files in your browser.


Also, just in case there are problems with the .pyz file or other unforeseen circumstances, I created another folder where I put the Python modules that I used to implement this project. If you want to use them as a program, you just need to run the __main__.py script from the command line. A requirements.txt file has also been added to the repository to preload the required libraries (requests and pyfiglet). The command line command to load the libraries is "python -m pip install -r requirements.txt".

It goes without saying that you must have the Python interpreter installed to run the application in either variant. 
