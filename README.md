## How to Run the Server and Activate the Django Project

1. **Clone the Repository**
    ```bash
    git clone <repository-url>
    cd CarReatals
    ```

2. **Create and Activate a Virtual Environment**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Database Migrations**
    ```bash
    python manage.py migrate
    ```

5. **Create a Superuser (optional, for admin access)**
    ```bash
    python manage.py createsuperuser
    ```

6. **Start the Development Server**
    ```bash
    python manage.py runserver
    ```

7. **Access the Application**
    - Open your browser and go to: [http://localhost:8000](http://localhost:8000)
    - For the admin panel, visit: [http://localhost:8000/admin](http://localhost:8000/admin)
8. **Thanks for using my project