# URL Shortener with QR Code Generator

This Django project is a URL shortener that also generates a QR code for each shortened URL. Users can input a long URL, and the application will return a shortened URL along with a QR code.

## Features

- Shorten long URLs
- Generate QR codes for shortened URLs
- Redirect users from the shortened URL to the original URL

## Requirements

- Python 3.x
- Django 3.x or higher
- qrcode
- pillow

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/AdarshPBaiju/URL-SHORTNER.git
    cd url_shortener
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run database migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser (optional):**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

7. **Open your web browser and go to:**

    ```
    http://127.0.0.1:8000/
    ```


## Usage

1. Enter a long URL into the input field.
2. Click the "Generate URL" button.
3. The page will display the shortened URL and a QR code.
4. Click the shortened URL or scan the QR code to be redirected to the original URL.

## Visit the Site

You can visit the live site here: [URL Shortener with QR Code Generator](https://shorturl-ibm9.onrender.com/)
