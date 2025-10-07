# Awesome Hanakai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A comprehensive collection of resources for the Hanami, Dry-rb, and ROM ecosystems

Hanakai is your all-in-one resource hub for everything related to [Hanami](https://hanamirb.org/), [Dry-rb](https://dry-rb.org/), and [ROM](https://rom-rb.org/) - the modern Ruby ecosystems for building maintainable, scalable applications.

## Contents

- [Hanami](#hanami)
  - [Hanami Core Repositories](#hanami-core-repositories)
  - [Hanami Community Gems](#hanami-community-gems)
  - [Projects Built with Hanami](#projects-built-with-hanami)
- [Dry-rb](#dry-rb)
  - [Dry-rb Core Libraries](#dry-rb-core-libraries)
  - [Validation & Types](#validation--types)
  - [Functional Programming](#functional-programming)
  - [Dependency Injection & System](#dependency-injection--system)
  - [Configuration & Utilities](#configuration--utilities)
- [ROM (Ruby Object Mapper)](#rom-ruby-object-mapper)
  - [ROM Core Framework](#rom-core-framework)
  - [Database Adapters](#database-adapters)
  - [Data Format Adapters](#data-format-adapters)
  - [Framework Integration](#framework-integration)
- [Learning Resources](#learning-resources)
  - [Documentation](#documentation)
  - [Tutorials & Articles](#tutorials--articles)
  - [Videos](#videos)
- [Community](#community)
  - [User Groups](#user-groups)
  - [Discussion Forums](#discussion-forums)
  - [Chat](#chat)
  - [Social Media](#social-media)
  - [Q&A](#qa)
- [Tools & Integrations](#tools--integrations)
  - [Development Tools](#development-tools)
  - [Editor Support](#editor-support)
  - [Deployment](#deployment)

---

## Hanami

The modern web framework for Ruby. Fast, secure, and lightweight with a focus on simplicity and productivity.

### Hanami Core Repositories

#### Main Framework
- [hanami/hanami](https://github.com/hanami/hanami) - The web framework for Ruby. Fast, secure, and flexible

#### Core Components
- [hanami/router](https://github.com/hanami/router) - Ruby/Rack HTTP router
- [hanami/api](https://github.com/hanami/api) - Minimal, lightweight, fastest Ruby framework for HTTP APIs
- [hanami/controller](https://github.com/hanami/controller) - Complete, fast and testable actions for Rack and Hanami
- [hanami/view](https://github.com/hanami/view) - Views, templates and presenters for Ruby web applications
- [hanami/validations](https://github.com/hanami/validations) - Validation mixin for Ruby objects
- [hanami/model](https://github.com/hanami/model) - Ruby persistence framework with entities and repositories
- [hanami/utils](https://github.com/hanami/utils) - Ruby core extensions and class utilities for Hanami
- [hanami/helpers](https://github.com/hanami/helpers) - View helpers for Ruby applications
- [hanami/mailer](https://github.com/hanami/mailer) - Mail for Ruby applications
- [hanami/assets](https://github.com/hanami/assets) - Assets management for Ruby web applications
- [hanami/cli](https://github.com/hanami/cli) - Hanami command line
- [hanami/db](https://github.com/hanami/db) - The database layer for Hanami
- [hanami/reloader](https://github.com/hanami/reloader) - Code reloading for Hanami 2
- [hanami/webconsole](https://github.com/hanami/webconsole) - Hanami web console for development

#### Testing Support
- [hanami/rspec](https://github.com/hanami/rspec) - Hanami RSpec extensions
- [hanami/minitest](https://github.com/hanami/minitest) - minitest support for Hanami apps

### Hanami Community Gems

#### Assets & Frontend
- [vite_hanami](https://github.com/ElMassimo/vite_ruby/tree/main/vite_hanami) - Vite.js as your asset pipeline in Hanami
- [hanami-sprockets](https://github.com/andrew/hanami-sprockets) - Sprockets asset pipeline for Hanami

#### Authentication & Authorization
- [jay_doubleu_tee](https://github.com/hanamimastery/jay_doubleu_tee) - JWT authorization wrapper for all Ruby apps
- [kan](https://github.com/davydovanton/kan) - Simple, light and functional authorization library

#### Database
- [rom_sql_graph](https://github.com/davydovanton/rom_sql_graph) - DB association graph for hanami and rom

#### CLI Tools
- [hanami-zsh](https://github.com/davydovanton/hanami-zsh) - Zsh plugin for hanami projects

#### API Development
- [hanami-jbuilder](https://github.com/vladfaust/hanami-jbuilder) - JBuilder templates support
- [had](https://github.com/gdwrd/had) - Hanami API Documentation
- [oas_hanami](https://github.com/a-chacon/oas_hanami) - Generate automatic interactive API documentation

#### Deployment
- [capistrano-hanami](https://github.com/mgrachev/capistrano-hanami) - Capistrano tasks for Hanami
- [hanami-docker](https://github.com/gruz0/hanami-docker) - Dockerize your Hanami application
- [mina-proteus](https://github.com/apontini/mina-proteus) - Mina plugin for deploying specific Hanami apps
- [hanami-lambda](https://github.com/elct9620/hanami-lambda) - Run Hanami applications on AWS Lambda

### Projects Built with Hanami

#### Open Source
- [cookie_box](https://github.com/davydovanton/cookie_box) - Follow and control issues from several repositories
- [OSSBoard](https://github.com/ossboard-org/ossboard) - Connect developers and OSS maintainers
- [contributors](https://github.com/hanami/contributors) - All hanami contributors in one place
- [makedecision](https://github.com/makedecision-org/core) - Make decisions faster
- [app.dartboard.io](https://app.dartboard.io/) - Online darts scorer app
- [pinfluence](https://github.com/rafaels88/pinfluence) - World influencers in a map
- [scripta.io](https://www.scripta.io/home) - Platform for creating and sharing documents
- [Flashcard Genius](https://github.com/Bajena/flashcard-genius) - Create, print and learn flashcards
- [hanami-realworld-example-app](https://github.com/blrB/hanami-realworld-example-app) - RealWorld example app

#### Example Applications
- [upment-hanami](https://github.com/AlexanderMint/upment-hanami) - JWT, GraphQL, RSpec example
- [distruct-me](https://github.com/MorozovaLiuda/distruct-me) - Self-destructing messages
- [hanami-jwt-example](https://github.com/nickgnd/hanami-jwt-example) - JWT authentication example
- [repressed_museum](https://github.com/vasspilka/repressed_museum) - i18n and docker integration example
- [bookshelf-delivery-example](https://github.com/bruz/bookshelf-delivery-example) - Web GUI, API and CLI example
- [hanami-chat-example](https://github.com/nickgnd/hanami-chat-example) - Chat application with LiteCable
- [Deutsch](https://github.com/mjacobus/deutsch) - Tool for learning German
- [Burn My Fat!](https://github.com/burn-my-fat/web) - Fitness tracking backend
- [decafsucks](https://github.com/decafsucks/decafsucks) - Example Hanami application rebuild
- [ddd-hanami-example](https://github.com/s-arikawa/ddd-hanami-example) - Domain-Driven Design implementation with Hanami

---

## Dry-rb

A collection of next-generation Ruby libraries, each intended to encapsulate a common task.

### Dry-rb Core Libraries

#### Validation & Types
- [dry-validation](https://github.com/dry-rb/dry-validation) - Validation library with type-safe schemas and rules
- [dry-types](https://github.com/dry-rb/dry-types) - Flexible type system with coercions and constraints
- [dry-schema](https://github.com/dry-rb/dry-schema) - Coercion and validation for data structures
- [dry-struct](https://github.com/dry-rb/dry-struct) - Typed struct and value objects
- [dry-logic](https://github.com/dry-rb/dry-logic) - Predicate logic with rule composition

#### Functional Programming
- [dry-monads](https://github.com/dry-rb/dry-monads) - Common monads in idiomatic Ruby
- [dry-transaction](https://github.com/dry-rb/dry-transaction) - Business transaction DSL
- [dry-matcher](https://github.com/dry-rb/dry-matcher) - Flexible pattern matching for Ruby
- [dry-effects](https://github.com/dry-rb/dry-effects) - Algebraic effects in Ruby
- [dry-operation](https://github.com/dry-rb/dry-operation) - Operation objects for business logic

#### Dependency Injection & System
- [dry-system](https://github.com/dry-rb/dry-system) - Organize your code into reusable components
- [dry-container](https://github.com/dry-rb/dry-container) - Simple, configurable object container
- [dry-auto_inject](https://github.com/dry-rb/dry-auto_inject) - Container-agnostic constructor injection

#### Configuration & Utilities
- [dry-configurable](https://github.com/dry-rb/dry-configurable) - Make Ruby classes configurable
- [dry-initializer](https://github.com/dry-rb/dry-initializer) - DSL for building class initializers
- [dry-cli](https://github.com/dry-rb/dry-cli) - General purpose CLI framework for Ruby
- [dry-view](https://github.com/dry-rb/dry-view) - Complete view rendering system
- [dry-core](https://github.com/dry-rb/dry-core) - Small support modules toolkit
- [dry-events](https://github.com/dry-rb/dry-events) - Pub/sub system
- [dry-monitor](https://github.com/dry-rb/dry-monitor) - Monitoring and instrumentation APIs
- [dry-inflector](https://github.com/dry-rb/dry-inflector) - Inflector for Ruby
- [dry-transformer](https://github.com/dry-rb/dry-transformer) - Data transformation toolkit
- [dry-files](https://github.com/dry-rb/dry-files) - File utilities
- [dry-logger](https://github.com/dry-rb/dry-logger) - Logging library

#### Framework Integration
- [dry-rails](https://github.com/dry-rb/dry-rails) - The official dry-rb railtie for Rails integration

---

## ROM (Ruby Object Mapper)

A powerful Ruby persistence library with pluggable adapters for different data stores.

### ROM Core Framework
- [rom](https://github.com/rom-rb/rom) - Data mapping and persistence toolkit for Ruby

### Database Adapters

#### Relational Databases
- [rom-sql](https://github.com/rom-rb/rom-sql) - SQL database support for ROM

#### NoSQL Databases
- [rom-elasticsearch](https://github.com/rom-rb/rom-elasticsearch) - Elasticsearch adapter
- [rom-mongo](https://github.com/rom-rb/rom-mongo) - MongoDB support
- [rom-neo4j](https://github.com/rom-rb/rom-neo4j) - Neo4j graph database integration
- [rom-redis](https://github.com/rom-rb/rom-redis) - Redis support
- [rom-couchdb](https://github.com/rom-rb/rom-couchdb) - CouchDB support
- [rom-cassandra](https://github.com/rom-rb/rom-cassandra) - Cassandra support
- [rom-dynamodb](https://github.com/rom-rb/rom-dynamodb) - Amazon DynamoDB adapter
- [rom-rethinkdb](https://github.com/rom-rb/rom-rethinkdb) - RethinkDB support
- [rom-influxdb](https://github.com/rom-rb/rom-influxdb) - InfluxDB time series database support

### Data Format Adapters
- [rom-yaml](https://github.com/rom-rb/rom-yaml) - YAML file support
- [rom-csv](https://github.com/rom-rb/rom-csv) - CSV file support
- [rom-json](https://github.com/rom-rb/rom-json) - JSON file support

#### Web & API Adapters
- [rom-http](https://github.com/rom-rb/rom-http) - Abstract HTTP adapter

#### Other Adapters
- [rom-git](https://github.com/rom-rb/rom-git) - Git repository support
- [rom-kafka](https://github.com/rom-rb/rom-kafka) - Apache Kafka support
- [rom-event_store](https://github.com/rom-rb/rom-event_store) - Event Store support

### Framework Integration
- [rom-rails](https://github.com/rom-rb/rom-rails) - Rails integration for ROM
- [rom-roda](https://github.com/rom-rb/rom-roda) - Roda plugin for ROM

### Utilities
- [rom-factory](https://github.com/rom-rb/rom-factory) - Data generator with persistence backend support
- [rom-yesql](https://github.com/rom-rb/rom-yesql) - SQL queries from files inspired by Clojure's Yesql

---

## Learning Resources

### Documentation
- [Hanami Guides](https://guides.hanamirb.org/) - Official Hanami documentation
- [dry-rb Documentation](https://dry-rb.org/) - Official dry-rb documentation
- [ROM Documentation](https://rom-rb.org/) - Official ROM documentation
- [Hanami Mastery](https://hanamimastery.com) - Articles and video tutorials

### Tutorials & Articles
- [What I learned building an app in Hanami](https://rossta.net/blog/what-i-learned-about-hanami.html)
- [Livereload and Hanami](https://defman.me/blog/hanami-love-livereload/)
- [Deploying Hanami with Docker](https://sebastjan-hribar.github.io/programming/2018/07/19/hanami-app-deployment-example.html)
- [Getting Started with Hanami and GraphQL](https://blog.simplificator.com/2016/12/07/getting-started-with-hanami-and-graphql/)
- [Websockets with LiteCable and Hanami](https://gabrielmalakias.com.br/ruby/hanami/iot/2017/05/26/websockets-connecting-litecable-to-hanami.html)
- [Integrating Pagy with Hanami](http://katafrakt.me/2018/06/01/integrating-pagy-with-hanami/)

### Videos
- [Hanami Mastery YouTube](https://www.youtube.com/channel/UC4Z5nwSfZrUO4NI_n9SY3uQ) - Video tutorials on Hanami and related libraries

### Books
- *Coming soon*

---

## Community

### User Groups
- [São Paulo, Brasil](https://twitter.com/hanamirb_sp) - Hanami-rb user group São Paulo
- [Facebook Brasil](https://www.facebook.com/groups/1415625271796799) - Brazilian discussion group
- [Russian Telegram](https://t.me/hanamirb_ru) - Russian community on Telegram

### Discussion Forums
- [Hanami Discourse](https://discourse.hanamirb.org/) - Official Hanami forum
- [dry-rb Discourse](https://discourse.dry-rb.org/) - Official dry-rb forum
- [ROM Discourse](https://discourse.rom-rb.org/) - Official ROM forum

### Chat
- [Hanami Discord](https://discord.com/invite/KFCxDmk3JQ) - Official Hanami Discord server
- [dry-rb Chat](https://dry-rb.zulipchat.com/) - Official dry-rb chat

### Social Media
- [Hanami on Mastodon](https://ruby.social/@hanami) - Official Mastodon account
- [Hanami on Bluesky](https://bsky.app/profile/hanamirb.org) - Official Bluesky account

### Q&A
- [StackOverflow](https://stackoverflow.com/questions/tagged/hanami) - Questions tagged with Hanami

---

## Tools & Integrations

### Development Tools
- [hanami-bench](https://github.com/davydovanton/hanami-bench) - Benchmarks for Hanami

### Editor Support
- [projectile-hanami](https://github.com/avdgaag/projectile-hanami) - Emacs minor mode for Hanami projects
- [vim-hanami](https://github.com/sovetnik/vim-hanami) - Vim plugin for Hanami navigation
- [vim-minispec](https://github.com/sovetnik/vim-minispec) - Run Minitest specs in Vim
- [RubyMine Integration](https://medium.com/@tetyanachupryna/how-to-run-hanami-in-rubymine-dff342cb0114#.7jb2bjq9f) - Guide for RubyMine users

### Deployment
- See deployment tools in the [Hanami Community Gems](#deployment) section

### Integration with Other Libraries
- [Sidekiq with Hanami](https://www.strauss.io/blog/2016-use-sidekiq-with-hanami.html)
- [Trailblazer with Hanami](https://github.com/apotonick/gemgem-hanami)
- [Factory Bot with Hanami](https://gist.github.com/rafaels88/8437edababcf38ee193b2ba0265e78b9)
- [Letter Opener](https://github.com/ryanb/letter_opener) - Preview emails in development
- [Mongoid](https://github.com/michalvalasek/hanami-mongoid) - MongoDB ODM integration

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
