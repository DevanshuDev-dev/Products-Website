# About Project - pyshop (Python Shopping)
This is a website created by me using Django where we are able to show products, it's price and an add to cart option where these datas are coming from the Admin Panel of my webpage in the products section.I as an admin can update, edit or delete data and accordingly that will be reflected on my webpage.Also, i am adding the css in my project through using bootstrap(4.0 version) and i am rendering the data in the form of bootstrap cards in our templates(base.html and index.html).We are mapping to two different url's for two different functions :-
If we are mapping to http://127.0.0.1:8000/products/ - then here i am showing PyShop in navbar and Products as heading along with multiple Products name, image, cost(in dollars) and Add to Cart.
If we are mapping to http://127.0.0.1:8000/admin - then here i am showing admin panel from where then datas are coming.
I am creating urls mapping in urls.py file and creating models in models.py file and configuring my Products in settings.py file and the database used is db.sqlite3 (Db Browser SQlite).I am mapping all the products to be displayed in views.py file through Product.objects.all().

#How to run the Project - 
Step 1 : Create project and open terminal and write - pip install django (To install Django framework).
Step 2 : Now copy and paste these folders and files after opening the project file location.
Step 3 : Execute this command on terminal - python manage.py runserver (To start the server) - Now after that there you will see like this -> 
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
Step 4 : So now just click on this link and after that follow the mapping urls link and there you will see the data accordingly.



So, Thankyou for having a look at my this basic project desgined using Django framework in Python programming langauge.  

