# Sails Migrations TestApp

This is an example of a sails project using sails-migrations for the sails-mysql 
adapter.

## Configuration
Edit `config/adapters.js` and provide your mysql db credentials
NOTE: This is already done in the testapp but for a new project, you'll need to 
add the following code in your `Gruntfile.js` after `grunt.initConfig`

```
  grunt.loadNpmTasks('gake')
  grunt.loadNpmTasks('sails-migrations')
```

## Usage
* `npm install`
* `grunt -h` to checkout the available tasks. (migrations:migrate, db:drop, 
  db:create, db:rollback, db:migrate)

- The `db/migrations` folder already has 5 migration files samples for you to 
  play with.
