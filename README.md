# User Authentication System (Laravel Sanctum API)

This project is a *RESTful API-based authentication system* developed with *Laravel. It includes essential features such as **user registration, **login, and **logout, all implemented using **Laravel Sanctum* for secure token-based authentication.

> *Only core and essential files* are available on GitHub for code review purposes.  
> *This project is for portfolio demonstration only and not intended for direct use.*

---

## Features

- *User Registration*
  - Standard input validation
  - Sends a welcome email to newly registered users

- *User Login & Logout*
  - Token-based authentication using Laravel Sanctum
  - Secure logout endpoint

- *Email System*
  - Welcome emails are sent using Laravel *queues and jobs*
  - The queue system uses the database driver for performance

---

## Tech Stack

- Laravel 12
- Laravel Sanctum
- MySQL (or other supported DB)
- Laravel Queues & Jobs
- Mail configuration
