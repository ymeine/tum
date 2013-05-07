# Types

[Type theory](http://en.wikipedia.org/wiki/Type_theory) is at the core of data management.

The more you want to manage data, the more you have to understand it.

And the more you want to automate data mangement, the more you have to formalize the way you describe data.

Here comes the typing system.

## Goal

The main goal is to build a comprehensive model for description of data types.

A type description can serve several purposes:

* description
* analysis
* runtime management

All is about automating these tasks. Respectively:

* Documentation generation (for both users and developers), integration inside the UI (interactive help), ...
* CMS tasks: add, create, update, delete, ...
	* validation
	* UI generation
	* ...

## Concepts

* Traits
* Inheritence
* Implementation
* Mixins
* Primitive types
* Complex types

# References

* [node-convict](https://github.com/lloyd/node-convict): notions of schemas for configuration objects

## Aria templates

[JSON Beans in Aria Templates](http://ariatemplates.com/usermanual/JSON_Bean_Definitions): lots of similar concepts!

Here are a few thoughts for improvement:

* validation of data, like for instance the regexp for a string, should be provided:
	* by a function in the general case: classical, data as input, boolean or detailed report object as output
	* by a common object
		* regexp for a string
		* min/max values for an integer
		* list of values (could be edited on the fly for instance, and follows some type specifications - to validate further the values and so on)
		* ...
* a default value is fine, but for UI purpose, I would add a `base` value, something like that, to be provided as the initial content in a form. This could be provided either statically or dynamically (computed - statistics, ...)
