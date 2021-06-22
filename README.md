# verify_vat

1) python -m venv env
2) . env/bin/activate
3) cd my_app
4) pip install -r requirements.txt
5) python app.py
6) login(/login) with curl or postman using email=test@example.com and password=qwerty or register new user (/signup)
7) get token after login 
8) curl -H "Authorization: {token_here}" \
     -X GET "http://localhost:5000/fiscal-number-information/GB/264770679"
