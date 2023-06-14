1. Open IRB.
2. Type the following expressions and check their results (press enter after typing each one):
* 2+2
* 10/3
* 10/3.0
* "Happy" + "coding"
* "Happy" + "\n" +  "coding"
* print "Happy" + "\n" +  "coding" + "\n"

3. Now let's try to play with variables, type the following (press enter after typing each one):
* a = 3
* a
* a = "Hello"
* a
* b = "World!"
* puts(a + b)

4. As IRB is an Interactive Ruby Shell, we can use the full power of Ruby here to write more complex scripts. Let's start playing with that:
* Create the following method:
  ```ruby
irb(main)> def hello(name)
irb(main)>   puts("Hello #{name}!")
irb(main)> end
=> :hello
```
- Use the method (e.g `hello("David")`).
5. Write a method `add`, it takes 2 arguments (`a` and `b`), and it returns the addition of the two arguments.

Note: I have used Vs Code instead of IRB terminal
