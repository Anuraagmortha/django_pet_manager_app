# Django Pet Manager App  
A Django application to manage pet-related information, facilitating CRUD operations on the database. This is designed to use in pet shops to magage pet data.

## Getting Started and Installation  

1. Clone the repository:
   ```
   git clone https://github.com/Anuraagmortha/django_pet_manager_app.git
   ```
2. Navigate to the project directory:
   ```
   cd django_pet_manager_app
   ```
3. Create and activate a virtual environment:
   ```
   python -m venv venv
   venv\Scripts\activate
   ```
4. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Apply the migrations:
   ```
   python manage.py migrate
   ```
6. Run the server:
   ```
   python manage.py runserver
   ```  

# Usage  

Navigate to `http://127.0.0.1:8000` in your web browser to view the functionalities.  

You can perform CRUD operations by navigating to `http://127.0.0.1:8000/admin` page after authentication.  
  
# Home Page  
This is the home page which you will be veiwing once you open it on your localhost.  
  
![image](https://github.com/user-attachments/assets/295d2e8e-c78c-443a-aa5f-7433db32eabe)  

# List of pets  
This is how you can see the list of pets in the home page:  
  
![image](https://github.com/user-attachments/assets/7cfeb5ea-aac1-49e1-8c2d-7c4f6844132e)  

# Pet Details  
When you click on any pet, You will be able to view the pet details as follows:  
  
![image](https://github.com/user-attachments/assets/856ee348-1cc7-4958-85ae-bd232e015293)  

