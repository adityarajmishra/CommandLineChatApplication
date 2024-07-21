Problem Statement: Command Line Chat Application

Your application should function as a straightforward command-line program. It should accept various types of inputs for different tasks, process the requests, store the necessary data, and then display the appropriate output. Think of it as a basic command-line tool where you enter commands and receive responses. There's no need to use a database to store data; you can utilize built-in data structures like arrays, sets, and maps provided by your chosen programming language.

Running the Application

To execute your application, use the primary class "com.chatter.platform.App.java" . It's crucial for the automatic evaluator and test cases to locate the main method within this class. The project directory you've received already includes this class with its main method. Therefore, ensure you use this main method to run your application as a command-line application.

Once your application is started, it should continuously wait for user input through the command line. This means it will enter a loop where it will:

Listen for a Command: The application waits for the user to type a command and press enter.

Process the Command: After receiving a command, the application will:

Interpret the command to understand what action is requested.

Validate the command to ensure it is correctly formatted and the data provided is valid.

Execute the action based on the command. This might involve adding a course, adding a student, assigning a course to a student, printing student details, or exiting the application.

Print the Output: Based on the action taken, the application will print the appropriate response to the command. This response could be a success message, an error message, or detailed information, depending on what the user requested and whether the command was valid.

Listen for the Next Command: After printing the response, the application goes back to waiting for the next user command.
