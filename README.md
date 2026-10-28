***
***
# ***Library Management System***
***
***

## **Summary**
    This is a library management API Backend for the management of users and the books

## **Routes and the Endpoints**

### *USERS*
***
***

#### 1. /users
* GET: Get all the list of users in the system
* POST (Big changes): Create/Register a new user

#### 2. /users/{id}
* GET: Get a user by their ID
* PUT (small changes): Update a user by their ID
* DELETE: Deleting a user by their ID (Check if the user still has an issued book) && {is there any fine/penalty to be collected}

#### 3. /users/subscription-details/{id}
* GET: Get a user subscription details by their ID
    * Date if subscription
    * Valid till ?
    * Fine if any ?

### *BOOKS*
***
***

#### 1. /books
* GET: Get all the books in the system
* POST: Add a new book to the system

#### 2. /books/{id}
* GET: Get a book by its ID
* PUT: Update a book by its ID
* DELETE: Delete a book by its ID

#### 3. /books/issued
* GET: Get all the issued books

#### 4. /books/issued/withFine
* GET: Get all issued books with their fine amount

### *SUBSCRIPTIONS*
***
***

* Basic - 3 Months
* Standard - 6 Months
* Premium - 12 Months

## Master Statement:
    git init; git add .; git commit -m "upload"; git remote add origin https://github.com/NSC-95-LM/library-management-system; git branch -M main; git push -u origin main -f

## Git Steps:

### Checking Step
    git status

### Pushing Step
    git add .

### First Step
    git config --global user.name "NSC-95-LM"

### Second Step
    git config --global user.email "chauhan.nishesh@outlook.com"

### Third Step
    git init

### Fourth Step
    git config --global color.ui auto

### Fifth Step
    git clone https://github.com/NSC-95-LM/library-management-system.git

### Sixth Step
    git remote add origin https://github.com/NSC-95-LM/library-management-system.git