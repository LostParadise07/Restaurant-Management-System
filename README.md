

# <div align= "center"> Restaurant Management System</div>


<p align="center"> A mini-web based project
    <br> 
</p>


##  About <a name = "about"></a>
This is an admin based  mini web project developed for the management of the records of food, billing and food sales. It is created with the motive of creating ease for the counter-management side of a restaurant.


<br>


##  Features <a name = "features"></a>

### For Registered Users :

- Admin Mode
   - Admin can register new staff.
   - Admin can CREATE, RETRIEVE, UPDATE and DELETE food items.
   - Admin can CREATE, RETRIEVE, UPDATE, PRINT and DELETE invoices.

<br>

- Staff Mode
   - Staff can CREATE, RETRIEVE, UPDATE and DELETE food items.
   - Staff can CREATE, RETRIEVE, UPDATE and PRINT invoices.
     
<br>

### For Unregistered users :
- Normal mode:
   - Can only view food-items list and food details.


<br>

##  Getting Started <a name = "getting_started"></a>

- Clone the repository or download the zip file

- For zip file extract it, then cd into the directory 

- make virtualenv and install the packages into the environment by:

    ```
     virtualenv venv

    venv\Scripts\activate (in windows) or $source venv/bin/activate (in Mac OS/linux)

    ```

- Install all dependencies by executing the following command:

    ```
    pip install -r requirements.txt
    ```

- For running the application simply execute the following commands:

    ```
    python manage.py migrate
    python manage.py runserver
    ```

- For creating a user execute:

    ```
    python manage.py createsuperuser
    ```

- if port is busy then use command 
    ```
    python manage.py runserver 7000
    ```

- You can now login to the system!

- Now you can use the app by visiting [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

