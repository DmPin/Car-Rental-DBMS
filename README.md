# Car Rental DBMS Application

Car Rental Database Management System built with **Django** and **SQLite**. Sample data is included.

## Requirements
- Python 3.9+  
- pip  
- (Optional) Git  

## Installation & Launch
1. **Get the Project**  
   - **Download ZIP:** Download from GitHub and extract.  
   - **Or Clone:**  
     ```bash
     git clone https://github.com/DmPin/Car-Rental-DBMS.git
     ```

2. **Open Project Folder:**  
  ```bash
  cd <path-to-project>/gui
  ```
   
3. **Install Dependencies:**
  ```bash
  pip install Django==4.2.26 sqlparse==0.5.1 asgiref==3.8.1
  ```
4. **Apply Migrations:**
  ```bash
  python manage.py migrate
  ```
5. **Load Sample Data:**
  ```bash
  python manage.py seed_data
  ```
6. **Start Application:**
  ```bash
  python manage.py runserver
  ```
