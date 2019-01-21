# The-Bridge-Keeper
A small javascript project, in order to show my progress in the language.

The Bridge Keeper reenacts, in an interactive way, the Monty Python movie: King Arthur and the Holy Grail scene of the Bridge Keeper. 


# What is this for?

This is a very small, very basic project in Javascript. 

## Primary Goal

To show potential teachers or potential employeers my progress through learning Javascript.

## Secondary Goal

To show potential employeers my ability to use gitHub and similiar systems for project development.

## Additional Goals

To show project iteration and feature definition as the scope and depth of the project continues

# Iteration 1 (Alerts and Prompts, Bridge Keeper v.1)

This iteration asks the questions using alerts and prompt boxes. 

## Notes from development:

There were multiple bug fixes that were needed. 

Most of it was simple things: 
* 1 infinite loop (forgot a counter increase). 
* Loop counters were off by 1 number. 
* Several times used = instead of == in If statements 
..* and learning that, unlike C# or Java, being a loosely interpreted scripting langauge, having questionNumber=4 in an if statement WILL change the var.
* the debuging (due to simple problems as commented) ended up using console.log to follow the questions and numbers. Good experience in logging for debuging purposes.

## Future Plans for next branch

* Modal popups instead of alerts. (bootstrap?)
* In page interaction. 
* Better handling of answers
* move to its own file, call script in page.

~~# First Branch:~~

~~Simple branch for readme Edits (the above title and below). Experimentation with GitHub features.~~

This branch has been merged.

# Iteration 2 (CSS and Jquery, Bridge Keeper v.2

## Second Branch: v0.2: CSS version

* This version of Bridge Keeper will move the entire interaction out of alerts and into the page, using CSS elements.
* Additionaly, several repeative coding actions will be moved into functions to clean up the code.
* Preperation will begin for moving this to its own js file, as well as working to impliment necessary libraries for other functions.

### First update:

* Functions created
* Jquery used for click(), as well as hiding and showing elements (by .css, not hide() or show()
..* Deliberate choice. hide() doesn't necessarily remove it from the page, where as .css('display', 'none') will take it out of consideration, removing blank spaces that could come from hidden elements (possibly)
* No errors when the page loads! ... but nothing currently happening. Button click for Block/None will have to be further debugged in next update.
