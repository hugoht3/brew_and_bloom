

# :warning: **Notice: Work in Progress - Incomplete**

**Hi [Code Institute Assessment Team],**

This project is currently **incomplete** due to a couple of challenges I encountered:

1. **Incomplete Tasks:** I haven’t finished all tasks yet, and I am waiting for your feedback to proceed. Once I have your feedback, I will complete the remaining work as soon as possible.
   
2. **GitHub Labs Issues:** I had to delete my entire project from GitHub Labs due to an error, which resulted in losing a significant amount of progress, including some completed user stories and work on the front end.

3. **Commits** Also Due to having deleted my work from github my commits went away as well you may notice this work have only a few commits that was for the only purpose of fullfiling this deadline. 

Given these setbacks, I would appreciate it if you could provide your feedback on the tasks I’ve completed so I can make the necessary changes and complete everything promptly.

Thank you for your understanding and support!
(I am having little difficulties with some life issues lately, but the promissed of finishing the course did not end.)

Looking forward to your feedback.

Best regards,  
[Victor Hugo]




# Brew & Bloom Coffee

## Project Overview
Brew & Bloom is an e-commerce application for specialty coffee products. Built using Django, it integrates Stripe for payments and provides a user-friendly, full-stack solution for managing an online store.

## Responsive Design

Here's the deployed site: [Brew_and_Bloom](https://brew-and-bloom-a47e2a36c3ac.herokuapp.com/)

---

# Setup Instructions

## Environment Variables

Create an `env.py` file in the project root with the following contents:

```python
import os

# Debug
os.environ['DEBUG']='True'

# Secret Key
os.environ['SECRET_KEY'] = 'Put your secret key here'

# Database URL
os.environ['DATABASE_URL'] = 'Put your database URL here'

# Host
os.environ['HOST'] = 'Put your host link here'

# Email
os.environ['EMAIL_USER'] = 'Put your email address here'
os.environ['EMAIL_PASSWORD'] = 'Put your email password here'

# Stripe Keys
os.environ['STRIPE_PUBLIC_KEY'] = 'Put your public key here'
os.environ['STRIPE_SECRET_KEY'] = 'Put your secret key here'
os.environ['STRIPE_WEBHOOK_SECRET'] = 'Put your webhook secret here'

# Cloudinary
os.environ['CLOUDINARY_CLOUD_NAME'] = 'Put your cloud name here'
os.environ['CLOUDINARY_API_KEY'] = 'Put your API key here'
os.environ['CLOUDINARY_API_SECRET'] = 'Put your API secret here'
```

### Run Migrations

```bash
python manage.py migrate
```

### Create a Superuser

```bash
python manage.py createsuperuser
```

### Run the Application

```bash
python manage.py runserver
```

---

# PostgreSQL Database

This project uses PostgreSQL for data storage.

**Steps to Obtain and Set Up the Database:**
1. Sign into your database provider and obtain connection details.
2. Configure the database URL in the `env.py` file.

---

# Color Scheme

The Brew & Bloom project employs a warm and inviting color scheme to reflect the brand's identity.

| **Color Name** | **Hex Code** | **Usage** |
| --- | --- | --- |
| Espresso Brown | #6F4E37 | Primary color for buttons and links |
| Latte Cream | #F5E1DA | Background highlights |
| Dark Roast | #3C2F2F | Text and footer backgrounds |

---

# Features

## Home Page
- Hero image with a warm welcome message.
- Featured products and promotions.

## Navigation
- Clear links to major pages: Home, Menu, About Us, Contact.
- Mobile-friendly design.

## Product Listings
- Detailed product pages with high-quality images and descriptions.
- User-friendly filters to browse coffee by type.

## Shopping Cart
- Add, remove, and update quantities of items.
- Seamless checkout with Stripe integration.

## User Accounts
- Register and log in to save preferences and order history.
- Profile management.

## Contact Page
- Inquiry form for customer support.

## Social Media Integration
- Links to Instagram, Facebook, and Twitter in the footer.

---

# Future Features

1. Subscription-based coffee delivery.
2. Loyalty rewards program.
3. Customer product reviews and ratings.

---

# Deployment

This project is deployed on Heroku.

## Deployment Steps
1. Create a new Heroku app.
2. Add necessary environment variables.
3. Deploy using GitHub or Heroku CLI.

---

# Technologies Used

- **Python & Django** for backend development.
- **Bootstrap** for responsive design.
- **PostgreSQL** for database management.
- **Stripe API** for payment processing.
- **Cloudinary** for media storage.

---

# Testing

- HTML and CSS validation using W3C validators.
- Python code linting with PEP8.
- Functional testing of checkout process.

---

# Credits

Images and icons sourced from Unsplash and FontAwesome.

---

# License

This project is licensed under the MIT License.
