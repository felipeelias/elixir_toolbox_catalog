# Elixir Toolbox Catalog

This repo contains the catalog for https://elixir-toolbox.dev. The idea is that anyone can suggest new categories and packages.

## Contributing

We appreciate any contribution to the catalog.
Please take a moment to read the points below to make the review process easy and effective for everyone.

### What is Elixir Toolbox

As of the writing of this page, <hex.pm> has around 13,300 packages :tada:.
It can be tough to find a package if you don't know it beforehand.

The idea of [Elixir Toolbox](https://elixir-toolbox.dev) is to help you find the most appropriate package that solves the right problem.
It does that by grouping packages into "groups" and "categories".

### How to think about Categories

Not all categories are created equal, and there is room for confusion.
We're trying to keep categories lean while not making it time-consuming to find what you're looking for.

A category groups packages that solve the same "problem".

An excellent example of a category is [JSON](http://localhost:4000/projects/parsing_serializing/json). That's because:

* It's easy to find in the category list
* Packages in that category solve the same "problem" (parsing and serializing of JSON documents)

A not-so-good example of a category is "Database Drivers". That's because:

* It may include MySQL, Postgres, Redis and other drivers. It's not a helpful comparison since you likely already decided which database to use.
* Popularity of the package depends on the popularity of the database.

### How to think about Groups

Groups put Categories together.
It exists to declutter the UI and to split categories that have the same "name" but have a different meaning in different contexts.

For example, "Clustering" has at least two meanings: data clustering algorithms and clustering Erlang nodes.

Elixir Toolbox catalog is heavily developed and lacks some groups, so suggestions are welcome.

## Copyright and License

Copyright (c) 2022, Felipe Philipp. Licensed under the [MIT License](LICENSE.md).
