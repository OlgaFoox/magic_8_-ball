Name: Olga Foox
Date Created:09/27/2024

Program Description:The Magic 8 Ball program simulates a fortune-telling toy that provides random responses to questions. Users can input their questions, and the program randomly selects a response from a predetermined list of answers. 

Logical Steps:
Step 1:The program checks for the existence of a text file (8ball_responses.txt). If it does not exist, a new file is created that includes predefined responses to yes/no queries.
Step 2: The program reads the responses from the 8ball_responses.txt file and stores them in a list for easy access.
Step 3: The program enters a loop where it prompts the user to ask yes/no questions repeatedly until the user types "quit."
Step 4: Upon receiving a valid question, the program randomly selects an answer from the list and displays it to the user.
Step 5: If the user inputs "quit," the program exits the loop and terminates gracefully.

Variables:
responses: A list that stores all responses read from the 8ball_responses.txt file.
question: A string variable that holds the user's input question.
answer: A string variable that stores the randomly selected response from the list of responses.
my_file: A file handler used to open and write to the 8ball_responses.txt file.


Functions:
Function Name: create_responses_file()
Description: Creates a text file containing predefined yes/no responses for the Magic 8 Ball.
Parameters: None
Returns: NoneFunction Name: read_responses()
Description: Reads responses from the 8ball_responses.txt file into a list.
Parameters: None
Returns: A list of strings containing the responses.Function Name: magic_8_ball()
Description: Prompts the user for a yes/no question and randomly displays one of the stored responses.
Parameters: None
Returns: NoneFunction Name: main()
Description: Orchestrates the execution of the program by calling create_responses_file() and magic_8_ball().
Parameters: None
Returns: None

Link to repository: [www.repository.com](https://github.com/OlgaFoox/magic_8_-ball/blob/main/OlgaFoox_ch1_ex1b.py)

