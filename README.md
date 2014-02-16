sinatra-template
================

Template Sinatra application.

This template project can be used to bootstrap a simple Sinatra web application. In uses Sinatra for route parsing, Unicorn for the service hosting and has stubs for both RSpec and Cucumber testing. HAML is used for HTML rendering.

config.ru - the rack up file

app/ - contains the app.rb where the Sinatra application lives

config/ - contains the unicorn.rb used by the .ru file. I often put a environment.rb in here to define db connections etc.

spec/ - RSpec files
features/ - Cucumber files
log/ unicorn log files
tmp/ PIDs for unicorn and sockets (if the unicorn.rb is configured to run using unix sockets instead of HTTP)


