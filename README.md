# What To Do When You Forget Your Password

## Description

In this lesson you will learn how to log into your WordPress site using a username and a password. You will also learn how to recover your password by email if it is lost.

## Objectives

After completing this lesson, you will be able to:

*   Gain access to a WordPress site if your user password is lost.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic computer skills.

## Screening Questions

*   Do you have a WordPress site or are you a user on a WordPress site?
*   Have you previously logged onto this site with a password?
*   Do you have an email address to which this WordPress site is linked?

## Teacher Notes

*   Performing a live demo and/or having students loggin in to their WordPress site during the lesson will be helpful in their understanding.
*   A live install of WordPress should work fine for this lesson. A local install is also acceptable.

## Hands-on Walkthrough

### Step One

By default, you can login to a WordPress site by going to the ```/wp-login.php``` path.  For example, if we forgot our password to the WordPress Support Forums, we could go to [https://login.wordpress.org/wp-login.php](https://login.wordpress.org/wp-login.php). 

1. Go to your WordPress site.  
2. Add ```/wp-login.php``` to the end of the site URL and press enter.  You will be taken to the login page, which looks like this: 

![WordPress Login](images/login.png)

### Step Two

1. At the bottom of the page, there is a link titled "Lost your password?"  Click the "Lost your password?" link. You will be taken to a new page, which looks like this: 

![WordPress Forgotten Password Page](images/lostpw.png) 

2. Enter your user name or email address. It is easiest to specify your email address in order to know which email account to check for the password reset email.  Click the "Get New Password" button after entering your email address.

#### If Something Went Wrong

After entering your email address, you may get this message: 

![Bad Email Error](images/lostpw.png)  

This message will appear if the email address provided is not associated with a user account on the WordPress site. 

Try entering a different email address that might be associated with the site. Or, contact the site administrator to ensure you have a user account. 

NOTE: *Many people have multiple email addresses. It can be difficult to keep track of which email address has been used for a particular site. If you get an error message with one email address, try another.*

### Step Three

1. After clicking "Get New Password," an email will be sent to you within a few minutes.  The message will look like this: 

![Lost Password Email](images/lostpwemail.png)  

This email includes your username. *Please take note of the user name in the email.* 

There will also be a link at the bottom of the email.  The link uses a one-time key called a "nonce."  A nonce is a very secure way to generate password reset links.  __The link will only work once.__  If you need to reset your password again, you will need to go back to the first step in this lesson and generate a new email.

### Step Four

Click the link at the bottom of your email.  You will be taken to this page: 

![Password Reset Page](images/newpw.png)  

Here, you will set a new password. After deciding on a new password and entering it into the field, click "Reset Password" and you're done!

### Conclusion

After resetting your password, it is a good idea to double check that it works.  Hover over the photo square in the upper right hand corner of your screen and click on "Log Out" when the menu appears.

![Log Out of WordPress](images/logout.png) 

1. Go back to the login page (ending in wp-login.php) and enter your user name (which you saw in the Password Reset email) and your new password. 

2. If your log in attempt does not work, double check the user name by comparing what you had entered into the login form with the user name from your email.  __When in doubt, copy and paste the user name from the email directly.__ Make sure you typed the password correctly.  If you've generated your password through a site and still have that window open, copy and paste the password.  Alternatively, if you're using a password management utility, copy and paste the password.

## Exercises

It is a good idea to be able to reset your password before you need to do so.  Here are the steps you can take to make sure you have first-hand experience before you lose an important password.

*   If you haven't already, sign up for the WordPress Support Forums: [https://wordpress.org/support/register.php](https://wordpress.org/support/register.php)
*   Follow the steps to reset your password as outlined in this lesson.

## Quiz

1. What is added to the end of your site URL, to log into your site? 

```
A.  /wp-login.com 
B.  wp-login.php 
C.  /wp-login.php 
D.  /login.php
```
2. A "nonce" is: 

```
A. Password management system 
B. Single-use password generator link 
C. Strong password generator 
D. Photo square in the upper right hand corner of your site
```
## Answers

```
Question 1: "C" - /wp-login.php 
Question 2: "B" - A single-use password generator link
```
