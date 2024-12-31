# 🎉 ShopMetrics
MYSTERY SHOPPING SOFTWARE

Welcome! To get started, clone the repository and push it to a new repository.

## Requirements

You'll need the following installed to run the template successfully:

* Ruby 3.2+
* PostgreSQL 12+ (can be switched to SQLite or MySQL)
* Libvips or Imagemagick

Optionally, the [Stripe CLI](https://docs.stripe.com/stripe-cli) to sync webhooks in development.
## Initial Setup

First, edit `config/database.yml` and change the database credentials for your server.

Run `bin/setup` to install Ruby and JavaScript dependencies and setup your database.

```bash
bin/setup
```

## Running ShopMetrics Rails

To run your application, you'll use the `bin/dev` command:

```bash
bin/dev
```

This starts up Overmind running the processes defined in `Procfile.dev`. We've configured this to run the Rails server, CSS bundling, and JS bundling out of the box. You can add background workers like Sidekiq, the Stripe CLI, etc to have them run at the same time.


## Contributing

If you have an improvement you'd like to share, create a fork of the repository and send us a pull request.
