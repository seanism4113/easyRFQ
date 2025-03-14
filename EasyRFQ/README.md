# EasyRFQ

[https://easyrfq.onrender.com/](https://easyrfq.onrender.com/)

EasyRFQ is a user-friendly platform designed to streamline the process of creating and managing customer Requests for Quotes (RFQs). With its intuitive interface, users can easily enter, track, and manage RFQs, simplifying the way businesses handle quoting and customer requests.

### EasyRFQs allows users to:

- Register an account and link it to your business
- Access and manage your company’s directory
- Easily create, view, and update items in Item Maintenance
- Manage and update customer information in Customer Maintenance
  - Set custom fixed or percentage markups per customer
- Create, view, and modify Requests for Quotes (RFQs) from customers
- Seamlessly convert RFQs into ready-to-send quotes for customers

## EasyRFQ | HomePage Logged In

![HomePage](readMeImages/EasyRFQ%20Home.png)

## EasyRFQ | Item Maintenance

![Item Maintenance](readMeImages/Item%20Maintenance.png)

## EasyRFQ | Customer Maintenance

![Customer Maintenance](readMeImages/Customer%20Maintenance.png)

## EasyRFQ | RFQ List

![RFQ List view](readMeImages/RFQ%20Details.png)

## EasyRFQ | Quote Template

![Quote Template](readMeImages/Quote%20Template.png)

## Setup

### Clone this repository

```bash
$ git clone https://github.com/seanism4113/Capstone_Project-1.git
$ cd DreamReads
```

### Create virtual environment and gather requirements

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```

### Set .env constants

```bash
$ touch .env
```

- In the env file you will need to create a constant for:

```bash
API_KEY =
DATABASE_URL =
SECRET_KEY =
```

API_KEY is a key obtained from GOOGLE BOOKS API. You MUST have a google account to obtain an API Key.
[Google Cloud](https://console.cloud.google.com)

- Find APIs & Services from the navigation menu dropdown in the top left
- Click on Credentials
- Click Create Credentials --> API Key

DATABASE URL

- Connect to your local database or an online database. Example of connection to postgres: DATABASE_URL ='postgresql:///dreamReads_db'

SECRET_KEY

- Create your own secret key. Example SECRET_KEY = 'secretkey'

### Run project

```bash
$ flask run --debug
```

### Open page in browser

- Go to http://localhost:5000/

## Resources Used:

- [Google Books API ](https://developers.google.com/books/docs/overview)

## Technology Used

- Python
- Flask
- WTForms
- SQLAlchemy
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
