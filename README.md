# Awesome Rails
A curated list of amazingly awesome open source rails related resources inspired by Awesome PHP.

[![Build Status](https://travis-ci.org/dpaluy/awesome-rails.svg?branch=master)](https://travis-ci.org/dpaluy/awesome-rails)

Check also: https://github.com/markets/awesome-ruby

- [Awesome Rails](#awesome-rails)
	- [Package Management](#package-management)
	- [Templating](#templating)
	- [Static Pages](#static-pages)
	- [Dashboards](#dashboards)
	- [HTTP](#http)
	- [Crawlers and Scrapers](#crawlers-and-scrapers)
	- [Email](#email)
	- [ETL](#etl)
	- [Files](#files)
	- [Imagery](#imagery)
	- [Testing](#testing)
	- [Documentation](#documentation)
	- [Security](#security)
	- [Code Analysis](#code-analysis)
	- [Assets Management](#assets-management)
	- [ActiveRecord](#activerecord)
	- [Geolocation](#geolocation)
	- [Search](#search)
	- [Date and Time](#date-and-time)
	- [Feature Toggling](#feature-toggling)
	- [Logging](#logging)
	- [SEO](#seo)
	- [Meta](#meta)
	- [PDF](#pdf)
	- [Performance](#performance)
	- [Analytics](#analytics)
	- [Optimization](#optimization)
	- [Production](#production)
	- [Command Line](#command-line)
	- [Authentication](#authentication)
	- [Authorization](#authorization)
	- [Text and Numbers](#text-and-numbers)
	- [Filtering and Validation](#filtering-and-validation)
	- [REST and API](#rest-and-api)
	- [Caching](#caching)
	- [Data Structure and Storage](#data-structure-and-storage)
	- [Notifications](#notifications)
	- [Deployment](#deployment)
	- [Parser](#parser)
	- [Third Party APIs](#third-party-apis)
	- [Miscellaneous](#miscellaneous)
	- [Development Software](#development-software)
	- [WYSIWIG](#wysiwig)
	- [Background Job](#background-job)
	- [Visual Goodies](#visual-goodies)
	- [Starters/Boilerplates](#startersboilerplates)
- [Resources](#resources)
	- [Websites](#websites)
	- [Books](#books)
	- [Web Reading](#web-reading)
	- [Rails Reading](#rails-reading)
- [Credits](#credits)
- [Contributing](#contributing)

## Package Management
*Libraries for package and dependency management.*

* [Bundler](http://bundler.io/) - The best way to manage your application's dependencies.
* [Bower Rails](https://github.com/42dev/bower-rails) - A Bower support for Rails projects.

## Templating
*Libraries and tools for templating.*

* [Rails Composer](https://github.com/RailsApps/rails-composer) - The Rails generator on steroids for starter apps.
* [Rails Apps Composer](https://github.com/RailsApps/rails_apps_composer) - Build your own application template.

## Static Pages
*Tools for pre-processing content to generate web pages.*

* [HighVoltage](https://github.com/thoughtbot/high_voltage) - Rails engine for static pages.
* [Refinery CMS](http://refinerycms.com/) - Rails-based CMS.
* [Camaleon CMS](http://camaleon.tuzitio.com/) - Rails-based CMS.

## Dashboards

* [Dashing](http://shopify.github.io/dashing/) - The exceptionally handsome dashboard framework.
* [Tasseo](https://github.com/obfuscurity/tasseo) - Live dashboard for Graphite

## HTTP
*Libraries for working with HTTP.*

* [Faraday](https://github.com/lostisland/faraday) - flexible HTTP client library, with support for multiple backends.
* [Typhoeus](https://github.com/typhoeus/typhoeus) - wraps libcurl in order to make fast and reliable requests.
* [Whois](https://github.com/weppos/whois) - An intelligent pure Ruby WHOIS client and parser

## Crawlers and Scrapers
*Libraries for crawling/scraping the Web.*

* [Wombat](https://github.com/felipecsl/wombat) - Lightweight Ruby web crawler/scraper with an elegant DSL which extracts structured data from pages.

## Email
*Libraries for sending and parsing email.*

* [MailCheck](https://github.com/mailcheck/mailcheck) - Reduce user-misspelled email addresses in your forms.

## ETL
*Data-processing libraries.*

* [Kiba](https://github.com/thbar/kiba) - the ETL framework for Ruby.

## Files
*Libraries for file manipulation and MIME type detection.*

* [MimeMagic](https://github.com/minad/mimemagic) - A MIME detection library.
* [Exporting CSV & Excel](http://railscasts.com/episodes/362-exporting-csv-and-excel) - RailsCast.
* [Sitemap Generator](https://github.com/kjvarga/sitemap_generator) - A sitemap generation library.

## Imagery
*Libraries for manipulating images.*

* [MiniMagick](https://github.com/minimagick/minimagick) - An image manipulation library.
* [CarrierWave::BombShelter](https://github.com/DarthSim/carrierwave-bombshelter) - is a module which protects your uploaders from image bombs. It checks pixel dimensions of uploaded image before ImageMagick touches it.

## Testing
*Libraries for testing codebases and generating test data.*

* [RSpec](http://rspec.info/) - A testing tool for the Ruby programming language.

## Documentation
*Libraries for generating project documentation.*

* [SAMI](https://github.com/fabpot/Sami) - An API documentation generator.

## Security
*Libraries for security, encrypting data and scanning for vulnerabilities.*

* [Brakeman](http://brakemanscanner.org/) - Static analysis security scanner for Ruby on Rails.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [SimpleCov](https://github.com/colszowka/simplecov) - Code Coverage.
* [Excellent](https://github.com/simplabs/excellent) - Source Code analysis gem for Ruby and Rails.

## Assets Management
*Libraries and tools for Assets management.*

* [Non-stupid non-digest assets](https://github.com/alexspeller/non-stupid-digest-assets) - compile both digest and non-digest assets in Rails 4.
* [Rack Zippy](https://github.com/eliotsykes/rack-zippy) - Rack middleware for serving static gzipped assets generated by the Rails asset pipeline

## ActiveRecord
*Libraries and tools for ActiveRecord tweaks.*

* [ActiveRecordExtended](https://github.com/GeorgeKaraszi/ActiveRecordExtended) - adds additional PostgreSQL quering abilities to ActiveRecord
* [ActiveRecord Import](https://github.com/zdennis/activerecord-import) - A library for bulk insertion of data into your database using ActiveRecord. 
* [Obfuscate ID](https://github.com/namick/obfuscate_id) - Make your ActiveRecord ids non-obvious.
* [Data Miner](https://github.com/seamusabshere/data_miner) - import XLS, ODS, XML, CSV, HTML, etc. into the ActiveRecord models

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoKit](https://github.com/geokit/geokit-rails) - Geokit plugin for Rails/ActiveRecord.
* [Zip Codes](https://github.com/monterail/zip-codes) - Identify city and States for given Zip code

## Search
* Libraries for search

* [PG Search](https://github.com/Casecommons/pg_search) - builds ActiveRecord named scopes that take advantage of PostgreSQL’s full text search 
* [searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy with Rails and Elasticsearch 

## Date and Time
*Libraries for working with dates and times.*

* [Temporal](https://github.com/jejacks0n/temporal) - Javascript timezone detection for Rails

## Feature Toggling
*Libraries that are helping to manage features.*

* [Feature](https://github.com/mgsnova/feature) - A feature toggle library written in ruby
* [Rollout](https://github.com/FetLife/rollout) - A feature flippers

## Logging
*Libraries for generating and working with log files.*

* [Lograge](https://github.com/roidrage/lograge) - Taming Rails' Default Request Logging

## SEO
*Libraries for SEO.*

* [Meta Tags](https://github.com/kpumuk/meta-tags) - Search Engine Optimization (SEO) plugin for Ruby on Rails applications.
* [Human Power](https://github.com/lassebunk/human_power) - Generate robots.txt

## Meta
*Libraries for MetaData.*

* [Preloadables](https://github.com/jacopotarantino/preloadables) - is exposing a set of view helpers for outputting HTML metadata related to domains, assets and pages that you would like to preload/prerender.

## PDF
*Libraries and software for working with PDF files.*

* [Prawn](https://github.com/prawnpdf/prawn) - A PDF generation library.
* [Wicked PDF](https://github.com/mileszs/wicked_pdf) - A tool to convert HTML to PDF.
* [Grimm](https://github.com/jonmagic/grim) - A tool for extracting pages from pdf as images and text as strings.

## Performance
*Libraries to dubug and solve performance issues*

* [Alocation Tracer](https://github.com/ko1/allocation_tracer) - allows to trace object allocation.
* [Memory Profiler](https://github.com/SamSaffron/memory_profiler) - A memory profiler for Ruby & Rails apps.
* [Derailed Benchmarks](https://github.com/schneems/derailed_benchmarks) - Benchmarks for your whole Rails app.

## Analytics
*Libraries for user analytics.*

* [Marketable for Devise](https://github.com/n8/devise_marketable) - Marketable lets Devise users easily store where your user came from and where they were going in your Rails app.
* [Meta events](https://github.com/swiftype/meta_events) - is a Ruby gem that sits on top of a user-centric analytics system like Mixpanel and provides structure, documentation, and a historical record to events, and a powerful properties system that makes it easy to pass large numbers of consistent properties with your events.

## Optimization
*Libraries to optimize your rails application.*

* [Counter Culture](https://github.com/magnusvk/counter_culture) - Turbo-charged counter caches for your Rails app.
* [OJ](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem.

## Production
*Tools for production*

* [Errbit](https://github.com/errbit/errbit) - error catcher
* [Peek](https://github.com/peek/peek) - Take a peek into your Rails applications

## Command Line
*Libraries for building command line utilities.*

TBD

## Authentication
*Libraries for implementing authentications schemes.*

* [Devise](https://github.com/plataformatec/devise) - Flexible authentication solution for Rails with Warden.

## Authorization
*Libraries for implementing authorization schemes.*

* [Pundit](https://github.com/elabs/pundit) - Minimal authorization through OO design and pure Ruby classes
* [The Role](https://github.com/the-teacher/the_role) - Authorization for Rails + GUI. Semantic, Flexible, Lightweight
* [CanCanCan](https://github.com/CanCanCommunity/cancancan) - CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

TBD

## Filtering and Validation
*Libraries for filtering and validating data.*

* [HTML5 Validator](https://github.com/amatsuda/html5_validators) - client-side validation

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [Apipie](https://github.com/Apipie/apipie-rails) - API Documentation Tool

## Caching
*Libraries for caching data.*

TBD

## Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

TBD

## Notifications
*Libraries for working with notification software.*

TBD

## Deployment

* [Capistrano](https://github.com/capistrano/capistrano) - Remote multi-server automation tool.
* [Capistrano Unicorn](https://github.com/tablexi/capistrano3-unicorn) - Unicorn tasks for Capistrano.
* [Capistrano Fifty Five](https://github.com/mattbrictson/capistrano-fiftyfive) - recipes for use with capistrano to automate installation of a full-stack Rails environment
* [Airbrussh](https://github.com/mattbrictson/airbrussh) - pretties up your SSHKit and Capistrano output
* [Pinglish](https://github.com/jbarnette/pinglish) - A simple Rack middleware for checking application health.
* [Flipper](https://github.com/jnunemaker/flipper) - A Allows appplications to be deployable by feature only.

## Parser
*Libraries for parsing*

* [Parslet](https://kschiess.github.io/parslet/get-started.html) - A small Ruby library for constructing parsers in the PEG (Parsing Expression Grammar) fashion.

## Third Party APIs
*Libraries for accessing third party APIs.*

TBD

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

TBD

## Development Software
*Software for creating a development environment.*

* [HomeBrew](http://mxcl.github.com/homebrew/) - A package manager for OSX.
* [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
* [Puppet](http://puppetlabs.com/) - A server automation framework and application.
* [Chef](https://github.com/opscode/chef) - A systems integration framework.
* [Backup](https://github.com/meskyanichi/backup) - A server backup tool.

## WYSIWIG
*WYSIWIG editors*

* [Bootsy](https://github.com/volmer/bootsy) - is a WYSIWYG editor for Rails based on Bootstrap3-wysihtml5 with image uploads using CarrierWave
* [Mercury Editor 2](https://github.com/jejacks0n/mercury/tree/mercury2) - full featured HTML5 editor
* [Froala jQuery WYSIWYG](https://github.com/froala/wysiwyg-rails) - (**Comercial**) provides the Froala WYSIWYG HTML Editor javascript and stylesheets as a Rails engine for use with the asset pipeline
* [Sir Trevor](https://github.com/madebymany/sir-trevor-rails) - Medium like editor

## Background Job

* [Sidekiq Statistics](https://github.com/davydovanton/sidekiq-statistic) - Improved display of statistics for your sidekiq workers and jobs.

## Visual Goodies
*Client side tools integrated with Rails*

* [NProgress](https://github.com/caarlos0/nprogress-rails) - [nprogress library](https://github.com/rstacruz/nprogress) progress bar
  wrapper
  
## Starters/Boilerplates
- [Rails Devise GraphQL](https://github.com/zauberware/rails-devise-graphql) - A Rails 6 boilerplate to create your next Saas product. Preloaded with graphQL, devise, JWT, CanCanCan, RailsAdmin, Rubocop, Rspec, and more.
- [Rails Template](https://github.com/mattbrictson/rails-template) - Application template for Rails 6 projects; preloaded with best practices for TDD, security, deployment, and developer productivity.

# Resources
Various resources, such as books, websites and articles, for improving your Rails development skills and knowledge.

## Websites
*Useful web and PHP-related websites and newsletters.*

* [Programming Community Curated Resources For Learning Ruby on Rails](https://hackr.io/tutorials/learn-ruby-on-rails)

## Books
*Fantastic books and e-books.*

TBD

## Web Reading
*General web-development-related reading materials.*

* [C is for Cookie, H is for Hacker](http://www.troyhunt.com/2013/03/c-is-for-cookie-h-is-for-hacker.html) - An article about cookies and security.
* [You Blew It Loading Your Login Form Over HTTP](http://www.troyhunt.com/2013/05/your-login-form-posts-to-https-but-you.html) - An article about using HTTPS correctly with login forms.
* [How HTTPS Secures Your Connection](http://blog.hartleybrody.com/https-certificates/) - An article explaining how TLS/SSL secures your connection.
* [How to Build a Secure Remember Me Feature](http://www.troyhunt.com/2013/07/how-to-build-and-how-not-to-build.html) - An article on how to build a secure remember me feature.
* [A Beginners Guide to HTTP Cache Headers](http://www.mobify.com/blog/beginners-guide-to-http-cache-headers/) - An article about HTTP cache headers.
* Beyond Series [1](http://blog.ircmaxell.com/2013/09/beyond-design-patterns.html) [2](http://blog.ircmaxell.com/2013/11/beyond-inheritance.html) [3](http://blog.ircmaxell.com/2013/11/beyond-object-oriented-programming.html) [4](http://blog.ircmaxell.com/2013/11/beyond-clean-code.html) - A series of articles about programming by Anthony Ferrara.
* [Semantic Versioning](http://semver.org/) - A website explaining semantic versioning.
* [Atlassian Git Tutorials](https://www.atlassian.com/git) - A series of Git tutorials.

## Rails Reading
*Rails-releated reading materials.*

TBD

## Rails Videos
*Rails online courses, screencasts, etc*

* [List of 80 free and paid Ruby on Rails courses from top e-learning platforms](https://classpert.com/ruby-on-rails) - A directory of RoR online courses by Classpert, an online course search engine.

# Credits

TravisCI validation code by [jondot](https://github.com/jondot). Origin: https://github.com/jondot/awesome-react-native

# Contributing
Please see [CONTRIBUTING](https://github.com/dpaluy/awesome-rails/blob/master/CONTRIBUTING.md) for details.
