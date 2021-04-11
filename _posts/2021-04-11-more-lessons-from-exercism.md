In the exercism assignment I learned a couple things that seemed practically useful.
1) If I am writing a method that needs to be called directly on the class, the method needs to have self.method_name. Otherwise, the method is not calling on anything. I am not exactly sure the disctinction but it is something to pay attention to.
2) .strip is a handy little guy
- It removes the whitespace at the beginning and end of a string (maybe more?). This is helpful for making sure stuff is formatted correctly and ignore erroneous spaces.
3) Using .map instead of .each
- I have been using .each to do something to each element in an array or hash.
- I have also been using .each to look at each element in an array or hash and check if it meets some condition.
- Using this has a catch all method has made my code a little messy.
- Moving forward, I need to figure it out if I am 
-- changing all the elements  => use .map
-or 
--simply trying to check a condition => use the appropriate method for a hash or array

Examples: 
To check a hash for a key:
- hash.key?(some_key)
To check an array for an element 
- array.includes?(some_element)

To downcase all elements in an array
new_array = array.map {|element| element.downcase }

instead of
new_array=[]
array.each do |element|
new_array.push(element.downcase)
end

4) Using .map shorthand
- .map(&:to_i) => I used this on one of the exercism, matrix I think.
- ["11", "12", "13"].map(&:to_i)
- => [11, 12, 13]
- There is more to it than this. Can change strings to symbols (I think?). But get more familiar with .map and see what I can do.

Good article on .map: https://www.rubyguides.com/2018/10/ruby-map-method/#:~:text=Map%20is%20a%20Ruby%20method,string%20%26%20make%20every%20character%20UPPERCASE.
