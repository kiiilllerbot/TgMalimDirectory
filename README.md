# README
A directory system based on Tanjung Malim, Perak.

# Admin Login Page
![alt text](https://i.imgur.com/4QPpTMH.png)

# Home Page
![alt text](https://i.imgur.com/zW61fSt.png)

# Store Page
![alt text](https://i.imgur.com/wO99sxA.png)

# Account Settings Page
![alt text](https://i.imgur.com/TeE1pEw.png)


* Ruby version: 2.7.5

* Rails version: 5.2.4.1

* Node version: 8.17.0

* Storage: Rails Active Storage

* Development Database: SqLite

* Deployment: Can be deployed in heroku after migrating database to PostgreSQL and AWS S3 for image storage.

# Instructions to run in your Local Machine:
*(1) Clone the Repo.

*(2) Install all the dependencies. Run
```
bundle install
```
*(3) Create and Migrate Database. Run
```
rails db:create
rails db:migrate
```
*(4) Spin up your local development server. Run
```
rails s
```