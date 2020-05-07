# restful-routes
A table of all 7 RESTful routes

Name | Path | HTTP Verb | Purpose
------------ | ------------- | ------------- | -------------
Index | /dogs | GET | List all dogs
New | /dogs/new | GET | Show new dog form
Create | /dogs | POST | Create new dog, then redirect somewhere
Show | /dogs/:id | GET | Show info about one specific dog
Edit |  /dogs/:id/edit | GET | Show edit form for one dog
Update | dogs/:id | PUT | Update a particular dog, then redirect somewhere
Destroy | dogs/:id | DELETE | Delete a particular dog, then redirect somewhere

# CRUD
Create, read, update and delete, these are the four basic types of functionality for our application.

### 1.Index
The index route is a get request which is used to display all the content. A get request is used to retrieve and request data from a specified resource in the server. For example — if I had a website about books, the index would show all of the books and their data that I have stored in my server.

### 2. New
The new route is also a get request, which is used to show a form for the user to create new content. In my books website — I would have a form for the user to create a new book that would allow them to enter something like a title, author and a book snippet.

### 3. Create
The create route is a post request. The post request method requests that a web server accepts the data enclosed in the body of the request message, most likely for storing it. This would then add the data entered to the database.

### 4. Show
The show route is a get request. An exmaple in our book app would be to show a book and all information about that book. Another example is if you imagine IMDB, once you’ve clicked on a film you will see a lot of different information about a specific film, that would be that films show page.

### 5. Edit
The edit route is also a get request. Edit will allow us to as you’ve probably guessed, is used to edit something on our app. This would then store the new information to the database and present it. For example in a book app if you wanted to add a longer snippet for a specific book this would be done through a form on the edit page.

### 6. Update
The update route is a put request. The put request is used to replace an existing resource or create a new one if it does not exist.

### 7. Destroy
The destroy route is a delete request. A delete request is delete is for deleting the resource, the delete method requests that you delete the origin from the server. This would be used to remove some or all information about something in our app.
