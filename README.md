# Quiztopia-CAC
Quiztopia is an interactive user-friendly multiple choice question-based quiz application that allows users to play quizzes spanning genres such as entertainment, history, monuments, music and sports. The user may choose to play rounds in one or more categories depending upon the choice inputted where each category contains five questions with options and explanations provided for the answers. The sports quiz contains questions that span various sports events and topics, the entertainment quiz deals with questions from the latest happenings in the entertainment world, the monuments quiz and the history quiz deal with various monuments and occurrences throughout history while the music quiz enables music lovers to put their knowledge to the test.
Quiztopia was created with the sole purpose of playing fun and refreshing quizzes that are less time-consuming but indulging and knowledge-inducing at the same time.

The backend of the quiz can be broadly classified as an amalgamation of various class methods, user-defined functions, loops, and conditional statements.
The program has defined a class __'quizGame'__ that contains the instances question, answer, options and explanation. These instances represent the question for each quiz category along with their respective answers, options and explanations. These instances are initialised using the init method.
The program additionally defines various user-defined functions within it, namely:

1) _quizScore_: This function takes the question, answer, explanation and the user input as parameters and checks whether the answers inputted by the user align with the answers in the CSV file. On this basis, the program classifies the answer as right or wrong and returns the explanation and score.

2) _finalScore_: This function is defined to return the final score after the quiz has been completed.

3) _readFromCSV_: This function is used to read the CSV file and extract the data from it. The CSV files contain the questions, options, answers and explanations for each question in the category.

4) _display_: This function is used to display the questions and the multiple-choice options to the user. Since the options have been inputted as a dictionary in the CSV file, the display() checks if the options are formatted as a dictionary before it is printed along with the questions.

5) _main_: The main function contains all the function calls of the aforementioned functions within it. It also contains the menu that assists the user in navigating through the application. It enlists different categories namely sports, entertainment, music, monuments and world history. The data for these categories are accessed from their respective CSV files which are traversed using a for loop that iterates through each row of questions, answers, options and explanations.

The application can be accessed and navigated using the steps:

Step 1: Entire the desired category number as mentioned in the main menu
![image](https://github.com/krupaannajohn/Quiztopia-CAC/assets/118895577/9d62d6ec-5d8e-43e8-b47c-8894c050b5fd)

Step 2: Attempt the questions of the chosen category by inputting the most suitable option
![image](https://github.com/krupaannajohn/Quiztopia-CAC/assets/118895577/e8df0de5-1bc3-4283-9b35-ea5cea7791b5)

Step 3: Once the quiz of the particular category has been completed, the final score will be displayed to the user.

![image](https://github.com/krupaannajohn/Quiztopia-CAC/assets/118895577/d4077527-8085-4548-bd6f-432ad56cf626)

Step 4: The user can choose to attempt questions from other categories or exit the quiz by choosing the respective options. The program returns a warning message and allows users to proceed to valid categories in case they input an invalid option.

Invalid option: ![image](https://github.com/krupaannajohn/Quiztopia-CAC/assets/118895577/60f164d9-9623-48c9-8120-cabb445097b7)

Exiting from Quiz: ![image](https://github.com/krupaannajohn/Quiztopia-CAC/assets/118895577/d3f92838-674c-491b-8005-e830a1f9f397)

The program is run and maintained using Python Jupyter Notebook and uses modules such as Pandas.
Quiztopia thus allows various functionalities such as navigating through the different categories of the Quiz along with additionally storing and accessing the data in CSV files, thus allowing additional file storage for easier access.
