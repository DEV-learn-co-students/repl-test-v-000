## This is a Readme with Code Challenges and a Quiz

Schlitz brunch photo booth lumbersexual cliche banjo Intelligentsia street art, bicycle rights salvia four loko vegan raw denim YOLO gluten-free. Echo Park 8-bit quinoa, raw denim next level vinyl Shoreditch authentic chambray farm-to-table craft beer XOXO.

## The three consecutive percent signs below indicate that start of a Repl block.

%%%

### This is the Quiz Title - It is required.

Here, you can write any necessary directions for the repl.  It will be parsed as markdown, and even accepts codeblocks!

Write a `for` loop that fills the given array `tayArray` with three strings, each containing "taylors gonna tay".

Here's an example of iteration in JS:

```js
for(i=0; i<10; i++;){
  // code here
}
```

Now write your own!

The space delineated by the tildes below is used to set any initial values for the repl.  Append the name of the language you want to use, to the opening trio of tildes.

~~~javascript

var tayArray = [];

~~~solution

var tayArray = [];

for(i=0; i<3; i++;){
  tayArray.push("taylors gon tay");
}

tayArray

~~~validation

expect(response).to.have.length(3);
expect(response).to.be.a("array");

~~~

%%%

### Some more markdown here

and so on and so on

%%%

### Ruby Repl

Write a method that reverses a string, and call it, passing "12345" as an argument.

~~~ruby

# Code your solution here

~~~solution

def reverse(string)
  string.reverse
end

reverse("12345")

~~~validation

assert.strictEqual(response,'54321');

~~~

%%%

???

# This is a quiz title.  It is an H1 that succeeds an opening quiz delimiter and a newline.

?: What is 1+1?  This is the first question.  A newline is required between this and the title above.

## Standard markdown will be parsed as expected between the question, and the answer block.

__The parends below are reserved characters that indicate radio buttons.__

( ) 3
(X) 2
( ) 11
( ) 1

?: What is 1+1?  This is how you can include code blocks as a choices.

( )
```ruby
  def three
    "3"
  end
```
(X)
```ruby
  def two
    "2"
  end
```
( )
```ruby
  def one
    "1"
  end
```
( )
```ruby
  def eleven
    "11"
  end
```

?: A newline is required between this question, and the answer block above.  Select numbers 3 and 4.

#### The square brackets below are reserved characters that indicate checkboxes.

[X] 3
[X] 4
[ ] 9
[ ] 7

???
