[![Github All Releases](https://img.shields.io/github/downloads/RitulAgarwal/Social-Posting-Platfom/total.svg)]()

# Social Posting Platform

A Django based Web Application that allows you to perform all these functions given below.    
- Register & Sign In
- Like & Share Posts
- Upload Photos with Captions
- Find & Search Other People
- View their Profiles
- Follow & Unfollow Users
- Doom Scroll your feed
- Customise your feed based on users you follow
- Download the posts
- Log Out


## Run it locally 

Clone the project

```bash
  git clone https://github.com/RitulAgarwal/Social-Posting-Platfom.git
```

You may Create a Python Virtual Environment
```bash
  python -m venv env # creates a virtual environment named env 
```
```bash
  env\Scripts\activate # activate the created environment in your terminal
```
You may now Install dependencies in this local environment

```bash
  pip install -r requirements.txt
```
Now, To run it locally, ensure manage.py file is in the pwd.

```bash
  dir # lists the project files
```
Now the WebApp will host locally on your browser
```bash
  python manage.py runserver
```


Starting development server at http://127.0.0.1:8000/

Click the link and it will host the WebApp on your browser

To create a superuser and access the Django Admin, enter username, email-address and password. 
```bash
  python manage.py createsuperuser
```
To modify the existing model/schema like adding more features or deleting existing features. 

```bash
  python manage.py makemigrations
```
```bash
  python manage.py migrate
```

## Screenshots


![User Page](https://i.postimg.cc/JnvzFRbV/Screenshot-2024-08-03-151655.png)

![Set Up Your Account](https://i.postimg.cc/MKDv6JwR/Screenshot-2024-08-03-150935.png)

![Feed / HomePage](https://media.dev.to/cdn-cgi/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fc2gq6rp4ahqxuopv51dy.png)


## Related

Here are some related projects

[Web App](https://github.com/RitulAgarwal/SeaHawks)  ;
[Cansat Tracker](https://github.com/RitulAgarwal/Cansat_tracker)


## Tech Stack

Django, Javascript, HTML, CSS
## Feedback

If you have any feedback, please reach out at ritul.agarwal.ug21@nsut.ac.in


## Contributing

Contributions are always welcome!
To add any additional functionality, or to indicate out errors in the code you may raise an issue. 


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ritulagarwal.github.io/portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritul-agarwal1702/)






