# Magazine Project

Open source project made with Django and React by code professionals to bring must know information to students & more

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

python >= 3.8 - Recommended: latest 
pip >= 20.1.1 - Recommended: latest 
node >= 12.17.0 - Recommended: latest
npm >= 6.14.4 - Recommended: latest


### Setup backend

Clone repository
```
git clone https://github.com/Daniloshlandia/magazine_project.git
```
Download python dependencies
```
pip install -r requirements.txt
```
Execute python migrations
```
python manage.py migrate
```
Run python server
```
python manage.py runserver
```

### Setup frontend

Download node packages
```
npm install
```
Run node.js server
```
npm run install
```

### Additional steps

Create an user in Django
```
python manage.py createsuperuser --username=joe --email=joe@example.com
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Django](https://docs.djangoproject.com/en/3.0/) - The web framework used to build the backend of the application
* [React](https://reactjs.org/docs/getting-started.html) - The JavaScript library use to build the UI with reusable components
* [AntD](https://ant.design/docs/react/getting-started) - A React UI library that contains a complete set of components and demos

## Authors

* **Danilo Altamirano** - [Danilosh45](https://github.com/danilosh45)

* **Eddy Moreno** - [Eddzequiel](https://github.com/eddzequiel)

See also the list of [contributors](https://github.com/Daniloshlandia/magazine_project/graphs/contributors) who participated in this project.

