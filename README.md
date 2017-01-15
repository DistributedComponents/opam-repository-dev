# Distributed Components OPAM development repository

All Distributed Components development OPAM packages live here.

## Repository

To activate the repository:
    ```
    opam repo add distributedcomponents-dev http://opam-dev.distributedcomponents.net
    ```

## OPAM metadata

We use the `tags` field of the `opam` file as follows:

 1. strings beginning with `keyword:` are considered as `keywords`
 2. strings beginning with `category:` are considered as `categories`

Example:

    tags: [ "keyword:cool" "keyword:stuff" "category:Some/Category" ]

Finally the `homepage:`, `author:`, `maintainer:` and `doc:` fields are
also used to generate the package entry.
