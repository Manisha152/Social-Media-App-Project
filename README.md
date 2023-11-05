# Social Media App with Django 

This repository contains a fully developed social media app using Django and Python. Here are the key features and implementation details of the final project:

## User Authentication
- Users can register and log in using their email and password.
- Customized authentication views to require email during registration.
- Redirects users to the landing page after successful login.
![image](https://github.com/Manisha152/Social-Network-Project/assets/87291128/951e9aaf-812c-406e-b1f2-38fcae0339bb)


## Post Management and Comments
- Users can create, read, update, and delete posts.
- Posts include content, creation date, and author information.
- Edit and delete buttons are available for post authors.
- A "post detail" view displays individual posts and their associated comments.
- Comments are user-generated and listed under posts, with the newest comments displayed first.
![image](https://github.com/Manisha152/Social-Network-Project/assets/87291128/294e8be8-37a1-4b53-96b7-b2fba2df3dd4)


## User Profiles
- Users can create and edit their profiles.
- Profile pictures and default images are supported through the media directory.
- URL patterns, views, and templates are in place for displaying user profiles.
- A profile edit view allows users to update their profile information.
![image](https://github.com/Manisha152/Social-Network-Project/assets/87291128/2b6d7b4c-034f-4a03-85fd-f98f8b88c397)



## Follow/Unfollow Feature
- Users can follow and unfollow other users on the platform.
- Modifications to the user profile model to support following relationships.
- Views and templates are provided for displaying follower status and action buttons.
![image](https://github.com/Manisha152/Social-Network-Project/assets/87291128/1edea702-71ed-4de8-b388-180911812b9d)


## "Like" and "Dislike" Feature
- Users can "like" and "dislike" posts.
- "Add like" and "add dislike" views are available for post interaction.
- HTML templates for post lists, profiles, and post detail pages display like and dislike counts.
![image](https://github.com/Manisha152/Social-Network-Project/assets/87291128/1ef67a70-8497-427b-bcfa-640a57e518eb)


These features collectively create a complete social media platform with user authentication, post management, user profiles, social interactions, and more.


To run the project, use the following command: `python manage.py runserver`. 

