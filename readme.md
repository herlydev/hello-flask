# Flask App

The following project was built during my course with Bottega. It has full CRUD funtionality

### Create Database
- If you need to create a database.  Hop into a python repl and run the following commands.
- When you're done you should have an app.sqlite file.  That file will be your database.

```
>>> from app import db
>>> db.create_all()
```