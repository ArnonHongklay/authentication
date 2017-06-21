# User Authentication

Demonstrate a simple password-based user authentication scheme. This problem does not require a persistence store (i.e. a database). Principles of ‘identification’ and ‘authentication’ should be demonstrated, along with basic data security considerations. Users can be authenticated against an existing hard-coded list of users (i.e. the application does not require options to create/edit/delete users).

Submission guidelines : The application can be built in any language or framework of your choice. You can optionally create the application with, or without, a graphical interface (i.e. a console application can be submitted). The solution should be submitted with all source code, build scripts, tests, and a README.txt file with instructions on how to run the application (including any required dependencies). recruitment process at Cerrita, a discussion of this application will form part of the interview.

How to run this: 

```
git clone git@github.com:arnonhongklay/user_authentication.git
cd user_authentication
bundle install
bundle exec rake db:migrate
rails server
```
Demo: https://shielded-dusk-46287.herokuapp.com/
