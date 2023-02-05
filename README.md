## A blog viewing website

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216826249-d4264615-2c77-4243-ab67-1f07d032f614.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216826994-4c61e071-ad14-4c2e-bbf6-2727afc4e52c.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216827032-c7927d2e-bddc-4a03-b1f1-9b3e76c2acf7.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216827105-92ed5b63-3514-42e4-8401-9076ea637a1d.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216827165-59a814f6-1254-4509-b59d-2ed3b8f05c26.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216827206-01443c55-6ff5-479a-94db-4b8622d395d6.png"></p>


<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216827326-47721fdc-21d3-4ec9-9746-64a9e33af573.png"></p>

It was built using Django Framework of Python, implementing Crispy Forms.

Users will need to register and if already registered then login, in order to create new blogs or edit their previous ones. However they dont need to be logged for viewing the website.

# Features:

1) Blogs get updated in real-time.
2) Blogs are arranged based on publishing time.
3) Website uses *pagination* to allow easy viewing and seperation of blogs on different pages.
4) Users can always change their credentials and update their login information with a proper *email-verification* process.
5) Ability to delete blogs, filter blogs, see your own blogs.

## Available Scripts

Inside the project directory, run:

`python .\manage.py runserver`

This open the website inside your local host.
Open https://localost:8000 to visit it in your browser.

**NOTE:**
You might need to install Crispy Forms and Pillow to run the server.

```
pip install Pillow
pip3 install --user django-crispy-forms
```

## Learn More 

Refer to [Django](https://docs.djangoproject.com/en/4.1/) documentationn to build your own such website!
