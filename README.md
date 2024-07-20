# Real Estate Website

This website is built for a real estate company for listing details on properties available for sale and inquiry.

## Table of contents

- [Overview](#overview)
  - [Built with](#built-with)
- [Usage](#usage)
  - [Header and top bar](#header-and-top-bar)
  - [Home page](#home-page)
  - [About page](#about-page)
  - [Featured listings page](#featured-listings-page)
  - [Login and registration](#login-and-registration)
  - [Logged in](#logged-in)
  - [User dashboard](#user-dashboard)
  - [Listings](#listings)
  - [Inquiring](#inquiring)
- [Issues](#issues)
- [Acknowledgments](#acknowledgments)

## Overview

BT Real Estate is a real estate company with properties listed on this website. Each listing shows several images of the property along with details on the house, as well as the agent assigned to the property and available to inquire about the listing. Users may inquire as guest users or register and log in to the website and manage their inquiries in their user dashboard.

#### Built with

- Python
- Django framework for administrative backend
- PostgreSQL database
- Bootstrap 4 theme for design
- deployed to DigitalOcean
- domain name from Namecheap

## Usage

#### Header and Top Bar

The top bar contains info about the company, including contact phone number, contact email, and icon links to socials.

The header contains the navbar for pages: Home, About, and Featured Listings on the left. On the right, users who are not logged in can navigate to the Login page or the page to Register as a new user.

<img src="/static/png/1homepagetop.png" width="250">

#### Home page

The top of the main home page shows a search field form for users, guest or registered, to search the available properties by keyword or phrase, city, US state or territory, number of bedrooms, and maximum price.

<img src="/static/png/1homepagetop.png" width="250">

Below the search form are some of the latest listings available, with some main details and a "More Info" button to see the individual listing page.

<img src="/static/png/2homepagemiddle.png" width="250">

At the bottom of the home page there is some more information about BT Real Estate and its services.

<img src="/static/png/3homepagebottom.png" width="250">

#### About page

The About page states the company's mission and objective, and includes a sidebar of the featured VIP employee/agent with a photo, name, and a short bio.

<img src="/static/png/4aboutpage.png" width="250">

#### Featured listings page

The Featured Listings display the latest listings, in order from most recent to earliest. Each listing has a "More Info" button to view more details and inquire about the listing.

<img src="/static/png/5featuredlistingspage.png" width="250">

Pagination on the featured listings page allows for 3 listings to show at any given time, and users may navigate the listings and see more by clicking either on the page number of one of the arrows on either side.

<img src="/static/png/6pagination.png" width="250">

#### Login and registration

Users log in by entering their username and password.

<img src="/static/png/7loginpage.png" width="250">

Registration requires users enter their first name, last name, username (if available), a valid email address, and a password.

<img src="/static/png/8registerpage.png" width="250">

#### Logged In

Once a user has logged in, the navbar on the right changes to allow the user to go to their dashboard or logout.

<img src="/static/png/9loggedinnavbar.png" width="250">

#### User dashboard

The user dashboard is for managing and tracking details about listing inquiries the user has made.

<img src="/static/png/userdashboard.png" width="250">

#### Listings

Featured listings show a main photo, the listing title or address, square feet, number of garages, number of bedrooms, number of bathrooms, the real estate agent listing the property, and how long ago the listing went up. To learn more about the listing, there is a "More Info" button at the bottom.

<img src="/static/png/10listingmoreinfo.png" width="250">

Individual listing pages show more photos that can be viewed as a carousel.

<img src="/static/png/11listingpagetop.png" width="250">

More details are displayed, along with a description on the property.

<img src="/static/png/12listingpagebottom.png" width="250">

#### Inquiring

Under the listing's real estate agent is a button to "Make an Inquiry". When clicked, an inquiry modal pops up with some information filled in, depending on the listing page the user is on. If the user is registered and logged in, the "Name" and "Email" fields are also filled in with their information. Users can write a message in the textbox and submit the inquiry. The inquiry is then emailed to that listing's agent and the property owner or landlord, and the inquiry is logged in the admin dashboard.

If a logged in user has already made an inquiry on a particular property, a notification tells the user they have already sent an inquiry on this listing, and does not send the duplicate inquiry.

<img src="/static/png/13inquirymodal.png" width="250">

## Issues

- [ ] Background images for the home page and the about page are not working/loading

## Acknowledgments

Author: [Emily Knott](www.emilyknott.com)

This project was built as part of [Traversy Media](https://github.com/bradtraversy)'s Python course: [Python Django Dev to Deployment](https://www.traversymedia.com/Python-Django-Dev-To-Deployment)
