# E-Shop Ecommerce Website With Django + React

Live Demo can be viewed at [e-shop](https://e-shop-jl5z.onrender.com)


# Features
* Full featured shopping cart
* Product reviews and ratings
* Top products carousel
* Product pagination
* Product search feature
* User profile with orders
* Admin product management
* Admin user management
* Admin Order details page
* Mark orders as delivered option
* Checkout process (shipping, payment method, etc)
* PayPal / credit card integration


# Download & Setup Instructions

* 1 - Clone project: git clone https://github.com/ashiqYousuf/e-shop/
* 2 - cd e-shop
* 3 - Create virtual environment: virtualenv myenv
* 4 - myenv\scripts\activate
* 5 - pip install -r requirements.txt
* 6 - python manage.py runserver

# Install react modules
* 1 - cd frontend
* 2 - npm install

# Media Files in Production
When it comes to handling media files in production, you have less options than you do for static files since you can't use WhiteNoise for serving media files. Thus, you'll typically want to use Nginx along with django-storages to store media files outside the local file system where your application is running in production.
**Prefer to store your media files on [Amazon S3](https://aws.amazon.com/s3/)? Check out [Storing Django Static and Media Files on Amazon S3](https://testdriven.io/blog/storing-django-static-and-media-files-on-amazon-s3/).**
