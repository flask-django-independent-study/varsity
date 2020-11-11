# Advanced Authentication

### Sessions vs Tokens

There is a video in the resources to explain sessions vs tokens. The main takeaway is that once we move away from serving html templates to rendering html with dynamic JavaScript, we need a new way of authenticating users. While sessions are stored on the back-end, tokens are kept in the front-end and then sent with every request to the back-end in the request header.

### 'block' and 'none' styling

There is an important note to be made about the way we are rendering our front-end in both week 4 and this week. We put everything in the index.html.j2 and set what we don't want to display: 'none'. When we want something to appear we set display to 'block'. This works fine for our application but in the real world this won't fly. Can you figure out why? All those DOM elements, although hidden, are still accessible by inspecting the page and opening up the developer tools. We could then, change the style of something to be displayed. The ideal way to go about this is instead of showing and hiding elements, to add and remove the elements from the DOM. This can get unnecessarily complex with vanilla JavaScript, which is why we are taking the shortcut approad. Once you learn a front-end framework like React, you'll have much easier tools to add and remove "Components" or items from the DOM.

**This week we will be building off of the-bank app from last week. The starting code may be a bit different. If you want to keep using your code, the starter files that have changed are main.js, index.html.j2, and models.py (although models.py has todos). Compare your code with the starting code to fully understand any changes**

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
