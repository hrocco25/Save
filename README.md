# Save

Save is a place where you can capture notes and to do lists to keep track of your thoughts.

## Functionality

Full CRUD is working on both models.  There are two models, List and Items.  Each list holds multiple items.   

We worked on having the redirect from item create/update/delete send you back to the list_detail page.  So no item_create/update.html templates were needed.

Due to list being a reserved word in Django, we used _list in it's place.

## User Accounts

We created accounts and have the app fully set up to be able to create a new user and login to the app.  However, there are not specific lists for each user.  Currently all users can see all lists.  We just got the link listed below for help but were unable to finish the setup.
- [resource](https://docs.djangoproject.com/en/3.0/ref/contrib/auth/)

## To be worked on:

- priority of each item
    - colors?
- alarm/time to complete by
- mark items as complete
- set up user login
- search bar
- css

## SuperUser:
- username: amyheather
- password: seir1118