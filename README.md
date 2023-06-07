# ips_capstone_auth
User Authorization Application

Basic user auth application using Django and JWT.  Required for login: username and password.

To set up JWT run:
pip install djangorestframework-jwt

Here are the endpoint URLs:
    User Registration: http://localhost:8000/api/register/
    User Login: http://localhost:8000/api/login/
    Token Refresh: http://localhost:8000/api/refresh/
    
example POST request JSON in ThunderClient:
{
    "username": "name",
    "password": "mypassword"
}
