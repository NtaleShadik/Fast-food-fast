[![Build Status](https://travis-ci.org/NtaleShadik/Fast-food-fast.svg?branch=develop)](https://travis-ci.org/NtaleShadik/Fast-food-fast)
[![Coverage Status](https://coveralls.io/repos/github/NtaleShadik/Fast-food-fast/badge.svg?branch=develop)](https://coveralls.io/github/NtaleShadik/Fast-food-fast?branch=develop)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


# Fast-food-fast

Fast-Food-Fast is a food delivery service app for a restaurant.
The user interface is hosted [here](https://ntaleshadik.github.io/Fast-food-fast/UI/index.html)

## THe project has the following routes

| REQUEST | ROUTE | FUNCTIONALITY |
| ------- | ----- | ------------- |
| *POST* | ```/api/v1/orders``` | _Creates a new  order_|
| *GET* | ```/api/v1/orders``` | _Returns all orders made_ |
| *GET* | ```/api/v1/orders/<order_id>;``` | _Returns a specific order_ |
| *PUT* | ```/api/v1/orders/<order_id>;``` | _Updates a specific order_ |

## BUILT WITH

* Flask - Python Framework used

## SETTING UP APPLICATION

1. Create a folder Fast-food-fast

    Clone repository to the folder

    **```git clone https://github.com/NtaleShadik/Fast-food-fast.git```**

2. Create a virtual environment that you are going to use while running the application locally

    **```$ python3 -m venv env```**

    **```$ source  env/bin/activate```**

3. Install all project dependencies using

    **```pip3 install -r requirements.txt```**

4. Run the appliction from the root of your folder using

    **```python3 run.py```**

## Author

*Ntale Shadik*
