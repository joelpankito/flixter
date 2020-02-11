# Flixter

A two-sided, video-streaming marketplace platform that features credit card payment capabilities, user role management, complex user interfaces, and advanced database relationships.

![flixter](/app/assets/images/flixter.png)


### Prerequisites

Setting up ruby on rails enviroment

[Getting Started with Rails](https://guides.rubyonrails.org/v5.0/getting_started.html)

### Installing

Once the ruby on rails enviroment has been set up.

Git clone the repository to your local machine:

HTTPS:
```
$ https://github.com/joelpankito/flixter.git
```
SSH:
```
$ git@github.com:joelpankito/flixter.git

```
Next, cd into the repository you cloned and install the necessary dependencies by running:
* In other to create your local database run:
```
rake db:create
```
```
rake db:migrate
```
* Install the necessary dependencies
```
$ bundle install
```
You will then be able to start the app locally by runnning:
```
$ rails server -b 0.0.0.0 -p 3000
```


## Built With

* [Rails](https://rubyonrails.org/) - web application framework

* [Postgres](https://www.postgresql.org/) - The database engine.

* [Bootstrap](https://getbootstrap.com/) - Bootstrap is a free and open-source CSS framework

* [JQuery](https://jquery.com/) - jQuery is a JavaScript library 

* [Devise](https://github.com/heartcombo/devise) - flexible User authentication 

* [Simple_form](https://github.com/heartcombo/simple_form) - building forms

* [Stripe](https://stripe.com/) - Online payment processing

* [AWS Integration](https://aws.amazon.com/) - cloud storage


## Authors

* **Joel Pankito** - *Complete work* - [Flixter](https://github.com/joelpankito)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
