+++
title = "Hello World"
date = "2016-11-28T16:18:34-05:00"
2016 = "11"
topics = ["press"]
tags = ["welcome", "hello world"]
img = ""
imgalt = ""
author = "jwogrady"

+++

Welcome to our new website. This is our first post.
<!--more-->

To commemorate our new website I asked our developers to submit a "Hello World" script in their favorite programming language.

<!--more-->

Bash
----

```Bash
echo "Hello World"
```

Basic
-----

```Basic
PRINT "Hello, world!"​
```

C
-
```C
#include

int main(void)
{
    puts("Hello, world!");
}
```
C#
--
```C#
using System;
class Program
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Hello, world!");
    }
}
```
java
----
```java
import javax.swing.JFrame;  //Importing class JFrame
import javax.swing.JLabel;  //Importing class JLabel
public class HelloWorld {
    public static void main(String[] args) {
        JFrame frame = new JFrame();           //Creating frame
        frame.setTitle("Hi!");                 //Setting title frame
        frame.add(new JLabel("Hello, world!"));//Adding text to frame
        frame.pack();                          //Setting size to smallest
        frame.setLocationRelativeTo(null);     //Centering frame
        frame.setVisible(true);                //Showing frame
    }
}
```
* seriously Java developers... How do you guys stay sane!

Javascript
----------
```
document.write('Hello, world!');
```
PHP
---
```php
<html>
 <head>
  <title>PHP Test</title>
 </head>
 <body>
 <?php echo '<p>Hello World</p>'; ?>
 </body>
</html>
```
Go
--
```go
package main

import "fmt"

func main() {
	fmt.Printf("Hello, world.\n")
}
```

elixir
------
```elixir
hello() ->
  io:format("~s~n", ["Hello world!"]).
```
