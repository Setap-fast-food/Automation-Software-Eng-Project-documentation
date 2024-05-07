Usage
=====

.. _installation:

Installation
------------

To use the project, you must first download it using github. As long as the project in its entirety has been downloaded,
Both the software and the realtime database will function correctly.

Using your flutter IDE of choice run 

flutter doctor, #used to make sure all necessary tools are downloaded
flutter clean, #clears the flutter build cache
flutter pub get, #forces flutter to search for and install dependenies in the .yaml file
flutter build web, #builds the current version of the project.

after having fetched the dependencies and built the project,
use flutter run to run the program


Use Cases
---------

To place an order and commit the details of the order to the firebase database,
The user must run the program and then navigate to the till screen.

Once on the till screen, use the Plus and Minus buttons to add foods to your order.

Finally, click the Pay button to send the order data along with the name to the database.


To View any previously created orders, navigate to the kitchen screen from the main menu.



