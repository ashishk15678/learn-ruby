## Variables in ruby
 
just like python , you don't need to pass on types
just type
```ruby
#for string
a = "something"

#for integer
b = 1 

# and so on
```

or for getting types 
```ruby
a = "hello world"
a.kind_of? String
# this will return true 

# you can try to type it , but it will throw error

a.class
# this gives class type

```
then if you want to convert variables from let's say

Integer to float
```ruby
a = 1
# to convert
a.to_f

```

or to string
```ruby
a = 1
a.to_s
```

### Variables scope

In ruby variable name highly depends on what it starts with 
for eg

If it starts with "$" it is a global variable

Here's the complete list


| Starts with             | Type                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |
