# MyFaceClone

MyFaceClone is a Django-based social media web application.

## Installation

### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/MyFaceClone.git
cd MyFaceClone
```

### 2. Create a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

## Database Setup

### 4. Apply Migrations
```sh
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser (Optional)
```sh
python manage.py createsuperuser
```
Follow the prompts to set up an admin account.

## Running the Server

### 6. Start the Development Server
```sh
python manage.py runserver
```

### 7. Access the App
Open your browser and go to:
```
http://127.0.0.1:8000/
```

## Additional Notes
- Make sure your `.env` file (if required) is set up properly.
- Static files might need to be collected:
  ```sh
  python manage.py collectstatic
  ```
- To stop the server, press `CTRL+C` in the terminal.


