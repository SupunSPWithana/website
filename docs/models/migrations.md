---
sidebar_position: 8
---

# Migrations

Migrations are the recommended way to make changes to your database schema in production.
They are a way to version control your database schema, allowing you to easily upgrade and downgrade your database as your application evolves.

Sequelize provides a [sequelize-cli](../cli.md), a Command Line Interface that can be used to create and run migrations. 
Of course, you are free to use any other migration tool. [Umzug](https://github.com/sequelize/umzug) is a great alternative that the Sequelize CLI uses under the hood.

Head to [the sequelize-cli page](../cli.md) for more information on how to use write migrations.