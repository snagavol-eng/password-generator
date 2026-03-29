
import random
import string

def is_strong(password):
    return (
        len(password) >= 7 and
        any(c.islower() for c in password) and
        any(c.isupper() for c in password) and
        any(c.isdigit() for c in password) and
        any(c in string.punctuation for c in password)
    )

def make_strong(password):
    password_list = list(password)

    if not any(c.islower() for c in password_list):
        password_list.append(random.choice(string.ascii_lowercase))

    if not any(c.isupper() for c in password_list):
        password_list.append(random.choice(string.ascii_uppercase))

    if not any(c.isdigit() for c in password_list):
        password_list.append(random.choice(string.digits))

    if not any(c in string.punctuation for c in password_list):
        password_list.append(random.choice(string.punctuation))

    # Ensure minimum length
    while len(password_list) < 7:
        password_list.append(random.choice(string.ascii_letters + string.digits + string.punctuation))

    random.shuffle(password_list)
    return ''.join(password_list)


# Take user input
user_password = input("Enter your password: ")

# Check strength
if is_strong(user_password):
    print(" Your password is already strong!")
    print("Password:", user_password)
else:
    print(" Weak password detected!")
    strong_password = make_strong(user_password)
    print(" Generated Strong Password:", strong_password)
