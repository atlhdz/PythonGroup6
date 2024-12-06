The project's goal was to make an online journal with a mood tracker.
We are beginners at understanding Python and are unsure how the database structure might work for each person.


1. You want to download the zip file
2. open a command prompt (We used Windows)
3. Use "Scripts\activate" to run the environment while in MoodTracker Directory/File
4. Then type "cd src" to access src files
5. Next type "python manage.py makemigrations"
6. After confirming type "python manage.py migrate"
7. You should then be able to type "python manage.py runserver" to start the server and it will provide you with a link for the main home page.

8. To access the Diary functions you need to create an admin account (Still unsure how to have users access that):
9. Type in the command line while the terminal is still active (Tip : you might need to press ctrl + c) "python manage.py createsuperuser"
10. Enter a Username
11. Enter an email
12. Enter your first name
13. Enter your last name
14. Enter your password
15. Enter the password again to confirm (If the password is simple it will ask if you are sure)
16. You can run the server again with "python manage.py runserver" and then at the top of the "URL" add /admin to access the admin site
17. Once accessed you can enter Diary Entries from the admin site and etc.

Please be kind :) and Tada! should kind of work!
