# Advanced Authentication

### Sessions vs Tokens

There is a video in the resources to explain sessions vs tokens. The main takeaway is that once we move away from serving html templates to rendering html with dynamic JavaScript, we need a new way of authenticating users. While sessions are stored on the back-end, tokens are kept in the front-end and then sent with every request to the back-end in the request header.

#### [Resources](https://github.com/flask-django-independent-study/varsity/blob/master/Resources/Week-5.md)

## Let's get started!

Clone the repository
```zsh
git clone git@github.com:flask-django-independent-study/week-5-varsity.git
```

Change into the new directory
```zsh
cd week-5-varsity
```

Create a folder called env that will hold all installed packages
```zsh
python3 -m venv env
```

Activate your virtual environment
```zsh
source env/bin/activate
```

Install all packages listed in the requirements
```zsh
pip3 install -r requirements.txt
```

**Follow the TODOs in the code, and finish the assignment!**
