# openapi-gen-ruby-sinatra

This repo demonstrates generating an OpenAPI spec from a [Sinatra](https://sinatrarb.com) app using the [openapi-rspec](https://github.com/exoego/rspec-openapi) gem. Despite using Sinatra for brevity, the generation method demonstrated here is applicable to Rails and likely other Rack-based frameworks.

When the RSpec tests are run, the OpenAPI file in `doc/openapi.yml` is created or updated.

## Getting Started

The following steps assume you have Ruby and Bundler installed. 

1. `bundle install`
1. `OPENAPI=1 bundle exec rspec`
