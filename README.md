C# code summary, for the past 2 weeks I have been apart of a team working with the MVC code first approach, during the two weeks I have implemented a class model and controller with the corresponding views to let users schedule a vacation day and send that data to the database, the data included, a start date and end date, vacation type, and the ID of the user that is signed in, this took me the longest time of any of the stories to get it working properly (about a week) but I was proud with how it turned out. https://github.com/tannerbergseng/c-LiveProject/blob/master/vactation.txt. 

The second story I worked on was just a simple front end fix to the forgot password page to add styling to match the rest of the application and to add a back button to return to the login page, this was all done within the single forgot password view with some simple cshtml codehttps://github.com/tannerbergseng/c-LiveProject/blob/master/forgotpassword.txt
https://github.com/tannerbergseng/c-LiveProject/blob/master/forgotpassword.PNG

 The third story I took I thought would be an interesting challenge which included a character limit size to the company news page along with a counter to let the user know how many characters they have left to use, the problem before was that the database would accept any amount of characters (Tested with 5 e-books, over half a million words, and over 3 million characters) but with some cshtml and some javascript I was able to add the limit as well as changing the color of the character counter to give some visual aid to the user about how many characters  they have left remaining.
https://github.com/tannerbergseng/c-LiveProject/blob/master/charactercount.txt
https://github.com/tannerbergseng/c-LiveProject/blob/master/charactercount.PNG

Focusing on front end development I was able to clean up and redesign the vacation page to make it fit in the site better and I turned out very happy with how it turned out, I also added a button to the side nav as well as making sure it was displaying the correct user and fixing the details page.
https://github.com/tannerbergseng/c-LiveProject/blob/master/VacationCleanup.PNG
Vacation Index code: https://github.com/tannerbergseng/c-LiveProject/blob/master/vacationIndex.txt
Vacation Details code: https://github.com/tannerbergseng/c-LiveProject/blob/master/vacationDetails.txt

Focusing on back end development I worked on making sure the schedule dates dont conflict with the vacation dates and if it did I created a new view to redirect the user creating the schedule to information on when that user is going to be on vacation. I did struggle with this a bit because I personally am not great at comparing dates so there was a lot of trial and error but in the end I got it working with no conflicts.
https://github.com/tannerbergseng/c-LiveProject/blob/master/vacationCheck.txt
https://github.com/tannerbergseng/c-LiveProject/blob/master/VacationCheck1.PNG
https://github.com/tannerbergseng/c-LiveProject/blob/master/VacationCheck2.PNG

At the end of the c# sprints I feel like I have gained so much confidence working in c# and web development and I was fortunate enough to be able to not only implement the vacation class into the database but also work on the vacation class in front end designing and making sure that the vacations don't conflict with any other scheduling which is very cool to be able to do. What I have gained from the C# live projects will be invaluble to me moving forward in my developing career and I was fortunate enough to be able to work with such a great team. 

