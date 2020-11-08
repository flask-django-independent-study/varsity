# Flask-Restless

#### The Importance of APIs

APIs are important not just when you want to access other data sets. But also when you want to give people access to your data, specifically those who are working on the same team as you.

This allows the front-end and back-end to be detached. In the real world, that projects you come across will most likely not be serving templated html files from the back-end. Instead, they create a back-end API to give the front-end access to the data. The front-end will likely  be running a JavaScript framework like React, Vue, Angular, or even Ember. Then, they will use XMLHttpRequests, fetch, or axios (like we did in Week 3) to make requests to the API on the backend to get any needed data.

#### What does REST stand for?

REST stand for representational state transfer. It's just a fancy way for saying the server can CRUD (create, read, update, and delete) database resources. The core idea is that every server url serves as an access point to the database resources.

#### What is Flask-Restless?

Creating a RESTful API can be cumbersome and overwhelming. Flask-Restless offers an APIManager to handle all of the heavy lifting for you!

#### REST API vs GraphQL

You may have heard of GraphQL, which is another type of API. GraphQL is a bit more involved to set up so we'll stick to REST for now. If you would like to learn more about the differences there is a video in the resources page.

#### [Resources](https://github.com/flask-django-independent-study/varsity/blob/master/Resources/Week-4.md)

## Let's get started!

Clone the repository
```zsh
git clone git@github.com:flask-django-independent-study/week-4-varsity.git
```

Change into the new directory
```zsh
cd week-4-varsity
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
