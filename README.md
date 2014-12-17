play-oauth-silhouette
====================

## Live Demo

You can see a live demo at [Heroku](https://play-oauth.herokuapp.com).

## Authorizations

#### Google

Create a Client ID at [Google Console Developer](https://console.developers.google.com/). Ensure the Project Name is equal to the Product Name (Project --> APIs and Authentication --> Authorization Screen --> Product Name)
- In order to perform authorizations with Google+, make sure you have enabled Google+ API and Contacts API.

#### Facebook

Create an Application at [Facebook Developer](https://developers.facebook.com/).
- Set a valid contact email at Settings.
- Make your application available to the general public at Status and Review.

#### LinkedIn

Register your application at [LinkedIn Developer](https://www.linkedin.com/secure/developer).

#### Twitter

TODO

## Features

* Sign Up
* Sign In (Credentials)
* Social Auth (LinkedIn, Google+, Twitter, Facebook)
* Dependency Injection with Guice
* Publishing Events
* Avatar service

## Template

This project was created starting from The Silhouette Seed project Activator template which shows how [Silhouette](https://github.com/mohiva/play-silhouette) can be implemented in a Play Framework application. It's a starting point which can be extended to fit your needs.

## Documentation

Consulate the [Silhouette wiki](https://github.com/mohiva/play-silhouette/wiki) for more information. If you need help with the integration of Silhouette into your project, don't hesitate and ask questions in our [mailing list](https://groups.google.com/forum/#!forum/play-silhouette) or on [Stack Overflow](http://stackoverflow.com/questions/tagged/playframework).

## Activator

See https://typesafe.com/activator/template/play-silhouette-seed

## License

The code is licensed under [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0).
