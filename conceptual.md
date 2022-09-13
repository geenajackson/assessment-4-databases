### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  > PostgresSQL is a database language with specific syntax different from other database languages. This allows relationships between tables and queries within the database.

- What is the difference between SQL and PostgreSQL?
  > SQL is a relational database language, allowing relations between tables, while PostgreSQL also offers more complex queries and JSON querying.

- In `psql`, how do you connect to a database?
  >     psql database

- What is the difference between `HAVING` and `WHERE`?
  >`HAVING` is used with aggregate clauses, like `COUNT` whereas `WHERE` is used with nonaggregate clauses.

- What is the difference between an `INNER` and `OUTER` join?
  > Inner joins take only the data between two tables and combines them; outer joins take all of the data between two tables and can include null or empty values as well.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  > Left outer takes all of the data from the table on the left side of JOIN and right outer takes all of the data on the right side of JOIN.

- What is an ORM? What do they do?
  > Object Relational Mapping; this allows you to interact with the database within your programming language.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  > Making client side requests allow the app to hand off request making to the browser while continuing to run in the background. Server side requests allow for more secure and sensitive information requests.

- What is CSRF? What is the purpose of the CSRF token?
  > Cross-Site Request Forgery Token. This token is used with forms to prevent requests from users without being authenticated, such as a user trying to submit a request to the form via an unrelated app.

- What is the purpose of `form.hidden_tag()`?
  > This allows you to put all of your hidden form fields in one block; all of the hidden fields can then be called at once.
