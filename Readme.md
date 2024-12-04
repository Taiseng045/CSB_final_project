# to run
1. run the main.py as python file on terminal
2. click on the http://127.0.0.1:5000 
3. copy the link run on different browsers to run as other users and admin 
# __init__.py
input your real email and application password key
line 19 and 20

app.config['MAIL_USERNAME'] = 'Example@gmail.com' real email password
app.config['MAIL_PASSWORD'] = 'password' your generated password

# auth.py
line 11

APPROVED_ADMIN_EMAILS = ['Example@gmail.com'] 

input your email that you want to make it admin
# view.py
line 104 and line 105

sender='Example@gmail.com',
recipients=[user.email, 'Example@gmail.com']

input it with admin email
line 186

sender='Example@gmail.com',

input it with admin email