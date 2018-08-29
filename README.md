# Project: Durant Loft Application 
# Team Members: 
Josh Asuncion, Brandon Fong, Emmett Ling, Joshua Yang 
# Demo Link:
https://www.youtube.com/watch?v=HjRlNPhKy8E

# Idea: 
An application used to manage and help administrate a shared meeting space called Durant Loft, with specific features to manage overseeing, inventory, and to more easily schedule meetups with others.

# Models and Description:

# User:
* has first and last name, email, year
* can have special status such as admin or current "working" shift.
* can have items, shifts, events

# Shift
* has start date/time, end date/time, and three workers(people who oversee meeting space)
* all 3 properties of the Shift are optional
* belongs to up to three users

# Event
* Allows the user to create an event that will describe event details as well as how to find rides to the event.

# Item
* has a name, category, and booleans indicated whether it is possible to borrow, or if it can be permanently checked out
* Mainly for lost and found purposes.

# Features:
* users can sign up and log in
* users can check out and return items from inventory
* users who are on working shift can view shifts and sign up for shifts
* users who are working or admin can view security codes

# Division of Labor:
Josh Asuncion: front end, security
Brandon Fong: Devise, shifts, seeds
Emmett Ling: front end, inventory
Joshua Yang: meetup (events), front end

![image](Screen Shot 2018-08-29 at 1.02.41 AM.png)
