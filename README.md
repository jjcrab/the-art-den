# the-art-den

This is an app for art school students to show and sell their artworks. And also a place for those who wants to have unique original art without paying crazy amount of money. Hopefully this app can help art school students to collect some tuition and support their early artistic journey. 

## Tech Stack
- Frontend: React, GSAP(stretch goal) 
- Backend: Python, Django, AWS S3, Docker

## List of backend models and their properties
### Student (user)
- Email (".edu" is required for Stretch goal)
- Username
### Artist
- Name
- Avatar
- School
- Graduation year
- Personal story
### Artwork
- Artist
- Title
- Artwork Image
- Price
- Added time
### Customer (2nd type of user)
- email
- username

## React component hierarchy
- header
- home
- about
- artworks
- artwork detail
- artists
- artist card
- student login/signup 
- customer/visitor login/signup
- footer

## User stories
### MVP
- As an art student, I want to have a student user account which only need my email address and password to sign up and login.
- As an art student, I want to have a personal page so that I can introduce my self and show my artworks.
- As a customer/visitor, I want to see all the artworks and I want to filter/sort them by price.
- As a customer/visitor, I want to see an artists list and can find the artists by school so that I can support my alumni(if any)
- As a customer/visitor, I want to 'like/save' the artwork I likes.
### Stretch Goals
- As a customer, I want to 'like/save' the artist.
- As a customer, I want to make sure the artist is a college student which means the students should use ".edu" email address to register this app.
- As an app users, I would like to see some animations in this app.
- As a customer, I want to 'buy' the artwork I like/select.

### Wireframes
![MacBook Pro - 1 (1)](https://user-images.githubusercontent.com/78054396/114994939-8f19a580-9e5a-11eb-88b9-d0df4c7e10fd.png)

