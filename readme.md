## What is this?

A full-stack restaurant application which users can search, geolocate, review and curate their favorite restaurants from around the world.

The application has three main models - Users, Stores, and Review - all of which are relational. It is designed to hit upon many of today's application needs such as user authentication, database storage, Ajax REST API, file upload and image resizing.

![Video](https://imgur.com/8a7YZln.gif)

## Mongo DB

Dang that's delicious runs on a MongoDB setup, which requires a local or remote database connection. To set one up, follow the steps below:


## Sample Data

To load sample data, run the following command in your terminal:

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100% clean with:

```bash
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the authors are as follows:

|Name|Email (login)|Password|
|---|---|---|
|Wes Bos|wes@example.com|wes|
|Debbie Downer|debbie@example.com|debbie|
|Beau|beau@example.com|beau|

## Required variables

```
NODE_ENV=development
DATABASE=mongodb+srv://
MAIL_USER=
MAIL_PASS=
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
PORT=7777
MAP_KEY=
SECRET=
KEY=
```
