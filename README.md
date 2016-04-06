### HTML/DSL example in Elixir

This is a example how to use Metaprogramming in Elixir to create a small DSL

#### How to execute it
```
iex(1)> c "template.exs"
[Template]
iex(2)> Template.render
"<div id=\"main\"> \n<h1 class=\"title\"> \nWelcome!</h1></div><div class=\"row\"> \n<div><p>Hello</p></div></div>"
```

I hope you enjoy it

