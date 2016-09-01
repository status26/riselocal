+++
date = "2016-08-28T16:18:34-05:00"
img = "hello-world.gif"
imgalt = "Hello World"
tags = ["welcome", "hello world"]
title = "hello world"
topics = ["press"]
author = "jwogrady"
2016 = "08"

+++

To commemorate the new launch of our new website our developers decided to say "Hello World" in their favorite programming language.
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
