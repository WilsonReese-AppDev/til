---
layout: post
title: Three things I learned from The Ruby Koans
---

Here are (at least) three things I learned from [The Ruby Koans](http://rubykoans.com/):

1) attr_reader can automatically define an accessor. This will be helpful for writing my own methods for classes which is something I want to become more comfortable with.
2) I can call .methods on objects and classes to see what methods are available to call. This allows me to check for ways to creatively remove roadblocks.
3) *args - this means that the method accepts a variable number of arguments in an array called args

<h1>****Here were my other notes/questions/epiphanies that I took while completing the Koans.****</h1>
about_arrays.rb
- Line 42-44
- Why is [4,0] an empty array and [5,0] is nil

about_hashes.rb
- Line 26
-- What is KeyError => how do we know what error to expect
-Line 40
-- Why do I have to put expected? Why can't I write entire hash?
- Line 99
-- Walk me through what is happening here

about_symbols.rb
- Line 28: what is going on here?
- Line 41: false, Constants do not become symbols

about_regular_expressions.rb
- Line 136: what are the $?

about_control_statements.rb
- Line 122: describe next statements
- ***Control statements are actually useful

triangle_project 1 and 2
- I feel like I did project 1 right
- Project 2, I had to understand the triangle rules
- Is there a way to do this without manually writing each side? I want to just if any side is less than zero without asking if a <=0 or b <= 0 or c <= 0 

about_exceptions.rb
- Can you walk us through what it all means?

about_iteration.rb 
- Another helpful one - better syntax for writing loops
- SO MANY USEFUL METHODS

about_blocks
- .call method is useful - can call a specific item rather than doing each one
- Other useful syntax

about_sandwich_code.rb
- used when it is the same thing, but is it only for opening files? Other examples of sandwich code?

about_classes.rb and about_open_classes.rb
- attr_reader can automatically define an accessor LINE 85
- this will be helpful for writing my own methods for classes which is something I am not terribly comfortable with

about_scope
- can call a constant using .const_get LINE 71
- What are considered constants? Float, Integer, String, Class, what else?

about_class_methods
- can call .methods on objects and classes to see what methods are available to call
- using self - not super confident in the best way to use it
- using .class.another_class_method -- if it is one step away call it by going up to the class and then using the method

about_message_passing
- *args just means an array
- &block, is just saying that there is a block
- what is super?

about_proxy_object_project
- wrote my own method missing one
- but I don't really get what is going on here - what is the point of a proxy object?
