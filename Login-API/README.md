API untuk login page mendapatkan data yang diinput dari user 

untuk menjalankan server django: python manage.py runserver

Testing di postman:
`http://localhost:8000/api/accounts/signin/`
METHOD: POST
JSON:
{

    "username": "testuser",

    "password": "testpassword"

}

`http://localhost:8000/api/accounts/signup/`
METHOD: POST
JSON:
{

    "username": "testuser",

    "email": "test@example.com",

    "password": "testpassword"

}
