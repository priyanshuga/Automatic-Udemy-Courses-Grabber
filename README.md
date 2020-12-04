# Udemy-Paid-Courses-Grabber

Script to add all udemy paid/free courses having coupons automatically to your udemy account

## **_Requirements_**

- Python (2 or 3)
- Python `pip`
- Python module `requests`
- Python module `colorama`
- Python module `bs4`
- Python module `browser_cookie3`

## **_Module Installation_**

    pip install -r requirements.txt

## **_Features_**

- Automatic login through browser using `browser_cookie3`
- One click to add all courses available with coupons to your udemy account.
- You can add any specific course to your account from the list of courses available.
- Many popular sites added to grab fresh/new courses (coupons).
- Many more features

## **_Usage_**

**_Add all/specific course_**

    python udemy.py

**_Or with cookie_**

    python udemy.py -c cookie.txt

**_To schedule with cron jobs_**

    python udemy.py --cron

**_To subscribe only paid courses_**

    python udemy.py --paid

**_Guide to create cookie.txt file_**

- Firstly go to udemy.com, then follow the images guide below
  <img src='images/image1.jpg' width='600' height='400'>

<img src='images/image2.jpg' width='600' height='400'>

<img src='images/image3.jpg' width='600' height='400'>

<img src='images/image4.jpg' width='600' height='400'>

<img src='images/image5.jpg' width='600' height='400'>

<img src='images/image6.jpg' width='600' height='400'>

# Note:

- This script was originally made by https://github.com/AmmeySaini/Udemy-Paid-Courses-Grabber since there aren't any updates I decided to takeover.
  And modify it for users who dont know python

- I am planning to update website and add support
