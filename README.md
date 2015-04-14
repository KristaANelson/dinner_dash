![alt tag](https://github.com/KristaANelson/dinner_dash/blob/master/example_image.png)

## Dinner Dash

This three week group project, creating a food ordering site, was our first Ruby on Rails application. This project focused on creating a session based cart, setting up authentication and securing authorization. My main focus on this project was the user login/logout feature, creating tests that follow the Arrange-Act-Assert pattern, and utilizing Factory Girl.


This project is for the second module at the Turing School of Software and Design.

Full project specifications are available here:
http://tutorials.jumpstartlab.com/projects/dinner_dash.html



This jam was brought to you by Emily Berkeley, Michael Dao, Krista Nelson and
Nathan Owsiany.

Emily Berkeley: github.com/EmilyMB

Michael Dao: github.com/mikedao

Krista Nelson: github.com/KristaANelson

Nathan Owsiany: github.com/ndwhtlssthr

## Notes

To get this to run locally, you need to run the following:

    brew install imagemagick

### Here's what you'll need to do after pulling to get it working on heroku
* `bundle install`
* `git push heroku master`
* `heroku pg:reset`
* `heroku run rake db:schema:load db:seed`
* `heroku open` and look at all the glorious menu/item images
