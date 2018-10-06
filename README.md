# ruby-capybara-site-prism
Capybara and Site Prism framework that uses Cucumber and Ruby...with of course the Page Object Model.

### Updates proposed...

- None, this is intended as a very basic, real world framework, ready for you to customise.

## Assumptions...

 1. You are not 100% new to Ruby or Cucumber
 2. You have the necessary Ruby tools in place and installed (i.e. bundler, rvm, etc)

## What this is / What's included....

 1. A fairly basic framework for testing web apps, using Ruby and Cucumber.
 2. Follows, generally, good Ruby, Cucumber and general automation practices.
 3. An idea of how a framework can be setup to handle a real world app.
 4. Some example of basic reporting.
 5. A good way to see how elements can be located, though CSS selectors are of course the preferred choice.
 6. A good example to see expectations in action.
 7. Good use of the Page Object Model.
 9. Supports Chrome, Headless and Firefox out of the box.
 10. Some basic profiles are included

## What this is not...

1. An all-in-one super duper framework.
2. Something that you can 100% copy over for any app (though I suspect you'd be able to use most, as is).

## Known limitations...

 - Probably loads.

## Want more?

Drop me an email, sherbhachu@googlemail.com for any comments, suggestions, etc.

## Instructions/Config required prior to use...

1. After cloning this repo...
2. Create a new gemset, i.e. 'ruby-capybara-site-prism'
3. Use the newly created gemset
4. ```gem install bundler```
5. ```bundle install```

Please ensure that you have the latest chromedriver...

```https://sites.google.com/a/chromium.org/chromedriver/downloads```

## Then to run a specific test...

```cucumber features/google_search.feature```