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


Till Screen Use Cases
---------------------

To place an order and commit the details of the order to the firebase database,
The user must run the program and then navigate to the till screen.

Once on the till screen, use the + and - buttons to add foods to your order.

Finally, click the Pay button to send the order data along with the name to the database.


To View any previously created orders, navigate to the kitchen screen from the main menu.

Kitchen Screen Use Cases
------------------------

To change the status of an order from 'active' to 'completed', use the button labelled as an arrow on the tab of the selected order.

To Switch between viewing active and completed orders, use the labelled tabs at the side of the screen.

