### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  - PostgreSQL is an open source ORDBMS (object relational database management system) that supports a large part of the SQL standard and offers many other features.

- What is the difference between SQL and PostgreSQL?
  - SQL is the language used for interacting with relational databases and PostgreSQL is a specific RDBMS that uses SQL and offers additional features and capabilities.

- In `psql`, how do you connect to a database?
  - `\c DB_NAME`

- What is the difference between `HAVING` and `WHERE`?
  - The `HAVING` clause only applies to groups based on a given condition, whereas `WHERE` filters all records from the table based on a given condition.

- What is the difference between an `INNER` and `OUTER` join?
  - `INNER` only joins rows that match the condition in both tables. `OUTER` will keep information that is not related to the other table in the resulting table.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  - `LEFT` consists of all rows from the first table (left) combined with matching rows from the second table (right). `RIGHT` is the matching rows from the first table (left) combined with all the rows from the second table (right).

- What is an ORM? What do they do?
  - ORM stands for Object Relational Mapping. SQLAlchemy is a powerful Python-based ORM that serves as a translation service between OOP in our server language and relational data in our database.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  - When a server side HTTP request is made the browser will reload the page. An AJAX request is done through Javascript and can thus make any changes from the request without reloading the page.

- What is CSRF? What is the purpose of the CSRF token?
  - CSRF (Cross-Site Request Forgery) is a type of attack where unauthorized commands are submitted from a user that the web app trusts. The purpose of a CSRF token is to prevent CSRF attacks from happening.

- What is the purpose of `form.hidden_tag()`?
  - It generates a hidden field that includes a token used to protect the form against CSRF attacks.
