# railsprojectmanagementapp
## The title of this app is acasi'

It is a rails based app using version 5.1.3

### Configuration

First, you must add this line to the bottom of the :development, :test group in your Gemfile:
        gem "rspec-rails", "~> 3.6"
        
Second, in its own finction in the Gemfile add this: 
        group :test do
          gem "capybara", "~> 2.13"
        end
        
Third, run bundle update in the command line

