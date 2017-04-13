# Markdown Tutorial

HTML is the building block of the web. It's what allows the web browser to render text, lists, tables, headers, images and more to the screen.

Unfortunately, HTML can become verbose and tedious to work with. Markdown allows us to use an easy to read and write text-based syntax that gets automatically converted to HTML.

For example the HTML bit: 
    
```HTML
<b>This is in bold.</b>
```

will render:

**This is in bold.**

In Markdown equivalently: 
    
    **This is in bold.**
 
will automatically be converted to the HTML bit:

```HTML
<b>This is in bold.</b>
```

and unsuprisingly render:

**This is in bold.**

## Let's get started! 

Remember to check the raw markdown and output so you can get a one to one matching and know which markdown is responsible for which output. 

***

Headers

# Header 1 

## Header 2 

### Header 3 

#### Header 4

***

Text Type

This is written in plain text.

_This is written in italic text._

**This is written in bold text.**

~~This is written in strike-through text.~~

> This is written in blockquote.

***

Links/References

You can provide a relative or absolute path to a file in your local workstation. Please advise that I am working in a Unix environment. You may need to modify the path syntax for your OS.

[Link To Directory/File in Local Workstation](Figs)

[Link to Website](http://google.com)

![Alt Text](Figs/palvin.jpg "File Title")

![Alt Text](https://i.ytimg.com/vi/F0KuO4RPPL8/hqdefault.jpg "File Title")

![Alt Text](http://38.media.tumblr.com/97d01e65fa16ffa7b00e8c7a6328f10f/tumblr_notfdxXaJN1r6rr1oo1_r1_250.gif "File Title")

As you can probably tell, I am a fan of Barbara Palvin. I apologize for personalizing this tutorial...

***

Data Structure

1. 
2. 
3. 
4. 

* 1
* 2
* 3
* 4

* A
  * a
  * b
* B
  * a
  * b

1.
  * a.
  * b.

2.
  * a.
  * b.

- [x] ToDo 1.
- [ ] ToDo 2. 
- [x] ToDo 3. 
- [ ] ToDo 4. 

Table| Col2 | Col2 |
------------ | ------------- | -------------
Row1 | (Row1,Col1) | (Row1,Col2)
Row2 | (Row2,Col1) | (Row2,Col2)

***

Code and Syntax Highlighting

```markdown
![Image Alt Text](/path/to/image)](path/to/linked/page)
```


```javascript
var s = "JavaScript syntax highligting!";
alert(s);
```
 
 
```python
s = "Python syntax highlighting"
print s
```


```ruby
s = "Ruby syntax highlighting"
puts s 
```

All types of syntax highlighting. 

***

Horizontal Rule Line

```markdown
***
```

***

# We're Done

You get updates on tutorials I am writing when you follow me on Twitter [@dhexonian](https://twitter.com/dhexonian).
