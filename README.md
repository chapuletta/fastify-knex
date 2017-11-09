# Fastify KnexJS Plugin

## How to use
```
fastify.register(require('fastify-knex'), options, err => console.error(err))

fastify.get('/', (request, reply) => {
  console.log(fastify.knex) // Knex DB instance
})
```

## Options

Knex client DB configuration JSON object.

http://knexjs.org/#Installation-client

# Version

1.0.0
