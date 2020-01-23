# Jungle

Jungle is a mini e-commerce application done using Rails 4.2, it features a product and cart page with a active Stripe API for payment. It also has a commerce owner page where you can manage your item inventory.


# Pictures 

![jungle1](https://user-images.githubusercontent.com/53335999/71031922-5b9dfe00-20e2-11ea-9260-526273dfa933.png)
![jungle2](https://user-images.githubusercontent.com/53335999/71031933-5e98ee80-20e2-11ea-9d62-22b13f8528c9.png)
![jungle3](https://user-images.githubusercontent.com/53335999/71031940-6062b200-20e2-11ea-8270-437edcca41ad.png)


## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
