# recipes

Simple restful api for recipes.  
My first project with [Express](http://expressjs.com/) and [MongoDB](https://www.mongodb.com/).

## Getting Started

```sh
git clone  https://github.com/okunoyuki/recipes.git
cd recipes
docker-compose up
```

## Usage

* GET /recipes
  * List all recipes
* GET /recipe/:id
  * Get specified recipe
* POST /memo
  * Create a new recipe (which contains `title` and `content` for now...)
* PUT /memo/:id
  * Update specified recipe
* DELETE /recipes
  * Delete all recipes
* DELETE /recipe/:id
  * Delete specified recipe

## Created With
* [Express application generator](http://expressjs.com/en/starter/generator.html)
