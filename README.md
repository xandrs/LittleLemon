# LittleLemon
Website for a small restaurant

Design and build a simple Django app

Goal:
1. Create the Menu page
2. Create the Menu Item page

Steps:
1. Open the models.py file and create a class called Menu with the following attributes:
Name
Price
2. Open the admin.py and register the Menu model.
3. make and perform migrations
4. The app-level urls.py should have the URL configurations for the pages Home, About and Booking.
5. Django admin panel:
Username: bistroadmin
Email address: admin@littlelemon.com  
Password: lemon@786!
6. run the server
7. Inside the Django admin panel, locate the Menu model under Restaurant
8. Add the following view logic inside the menu() view function:
Create a variable called menu_data and assign it the value of objects.all() which is called over the Menu model class.
Create a variable called main_data and assign a dictionary that contains the following key-value pairs: 'menu': 'menu_data'
9. Open the app-level urls.py file and add the URL path for the menu view function using the path() function.
10. Create a file called menu.html 
11. Open the file models.py and update the Menu model
12. Open the views.py file and create a view called display_menu_items
13. Open the app-level urls.py file and add a path() function inside the urlpatterns
14. Create a file called menu_item.html inside the templates directory 
15. 
