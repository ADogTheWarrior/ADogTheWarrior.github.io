---
layout: post
title:      "Different Generators"
date:       2020-01-23 11:45:53 -0500
permalink:  different_generators
---

The purpose of this blog is to talk about the rails generate command. First thing is that generate can just be shortened to "g" when using it. Also in this blog I will use quotation marks but those are not needed in the actual command. Everything inside the quotation marks is just a description what should go there. I also have the command broken up between lines so it's easier to read but in reality when inputting the command it should just be a space.

rails g
"name of generator"
"options"
--no-test-framework

This is the basic format for any rails generate command. There are four generators I'll talk about. They are Migration, Model, Controller, and Resource. These would be what goes in the "name of generator" space. Then the "options" part is where the real interesting stuff happens. Each generator has different options and I'll go over some basic ones. The last bit is there so the generator doesn't build out extra test suites. While testing is important it is convient for small labs and lessons to forgo this so it doesn't interfere with the preexisting tests already there.


Migration Options

rails g migration
add_"name of new attribute"_to_"plural name of model in table"
"name of attribute":"variable type"
--no-test-framework

This command will add a new attribute to a model in the database. It also creates a database migration. Run rake db:migrate afterwards to update the database.


rails g migration
change_"name of attribute in table"_data_type_to_"plural name of model in table"
"name of attribute in table":"new variable type"
--no-test-framework

This will change the attribute type of a model in a database. It creates a database migration. Run rake db:migrate afterwards to update the database.


rails g migration
remove_"name of attribute in table"_from_"plural name of model in table"
"name of attribute":"variable type"
--no-test-framework

This will remove an attribute of a model from the database. It creates a database migration. Run rake db:migrate afterwards to update the database.


Model Options

rails g model
"capitalized singular name of new model"
"first attribute name":"first attribute type"
"second attribute name":"second attribute type"
...
--no-test-framework

This will create a new model. It also creates a database migration for the model and attributes. Run rake db:migrate afterwards to update the database.


Controller Options

rails g controller
"lowercase singular name of controller"
"lowercase singular name of first custom view"
"lowercase singular name of second custom view"
...
--no-test-framework

This will creatie a new Controller. It also creates relevant routes, views in a directory, coffescript file, view helper method file, and scss file.


Resource Options

rails g resource
"capitalized singular name of controller/model"
"first attribute name":"first attribute type"
"second attribute name":"second attribute type"
...
--no-test-framework

This will create a new Controller and Model. It also creates a database migration, model file, controller file, empty view directory, view helper file, coffeescript file, scss file, and  a full resources call in routes. Run rake db:migrate afterwards to update the database.

