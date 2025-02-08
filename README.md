# Profile and Project Management System

This web application allows users to view developer profiles, browse projects, and send messages for collaboration. Users can also upload and manage their own projects. It’s built using Django for the backend with Django Rest Framework for APIs. The frontend is built with HTML, CSS, and JavaScript. This project helps developers and clients connect and manage projects easily.

## Steps to Run the Project

1.  Clone the repository with the following command:
   ```bash
    git clone https://github.com/VachhaniRahul/Profile_and_Project_Management.git
   ```
2. Navigate into the project folder:
```bash
  cd .\Profile_and_Project_Management\
```
3. Create a virtual environment:
   * For Windows:
     ```bash
         python -m venv venv
       ```
   * For Linux/Mac:
     ```bash
        python3 -m venv venv
     ```

4. Activate the virtual environment:
     * For Windows:
       ```bash
        .\venv\Scripts\Activate.ps1
       ```
     * For Linux/Mac:
     ```bash
       source venv/bin/activate
     ```
5. Install required dependencies:
    ```bash
   pip install -r requirements.txt
    ```
6. Run migrations:
   ```bash
   python manage.py makemigrations
    python manage.py migrate
7. Start the development server:
   ```bash
   python manage.py runserver
   ```
## Your project should now be running locally!


   

