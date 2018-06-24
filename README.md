# QuizApp

My Android App consists of two Layouts, Main activity and Memo activity

In the Main activity.
This is an Android App which ask the user six questions about the country South Africa, this app consist of a EditText view which a user has to write their name first before continuing to the quiz.
After writing his/her name, the user can then start answering the questions, questions are in a form of a free response text, check box (for questions with multiple answers) and radio buttons (for questions with only one answers).
In my App, after the all the questions there is a button (Submit answers) which opens another activity and also gives you a toast message indicating the number questions you got correct out of six, and note that all questions have correct answers.
The submitt button does not work unless the Name textfield is filled and all questions are answered. After answering all questions and filling the Name textfield, when you click the submit answers button it will open the Memo activity.

In the Memo activity.
The memo activity consist of a text which thanks the user for completing the quiz and also contains a selectable text (click here), when you click on the text you shall be able to get the the Memo i.e the answers for all the six questions, in brief. Below the texts, there's a button (Submit quiz), in the button I have implemented an email Intent which is jusssuppose to send an email that the quiz has been submited, that's all.
