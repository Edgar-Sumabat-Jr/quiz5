## Project Setup

Follow these steps to get the project up and running on your local machine.

### 1. Clone the repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Edgar-Sumabat-Jr/quiz5.git

cd quiz5
python -m venv venv

venv\scripts\activate

pip install -r requirements.txt

cd backend
python manage.py runserver

```

### How to test login and register

To test login enter this url then enter username:123 password:123, if it doesn't work create your account first in admin page
```bash
http://127.0.0.1:8000/api/token/
```

To test register enter this url, then enter your desired details.
```bash
http://127.0.0.1:8000/api/register/
```
