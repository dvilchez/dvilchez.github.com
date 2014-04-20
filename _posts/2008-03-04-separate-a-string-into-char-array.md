---
comments: true
share: true
layout: post
title: String tips&tricks
categories:
- tips&amp;tricks
tags:
- c#
- desarrollo
status: publish
type: post
published: true
meta:
  _edit_last: '2'
author:
  login: david
  email: dvilchezm@gmail.com
  display_name: David Vílchez Mendoza
  first_name: David
  last_name: Vílchez Mendoza
---
* StringCollection to Array
{% highlight csharp %}
StringCollection.CopyTo
{% endhighlight %}
* Separate a string into char array
{% highlight csharp %}
String.ToCharArray
{% endhighlight %}
* String to byte array
{% highlight csharp %}
Encoding.ASCII.GetBytes(string)
{% endhighlight %}
* Byte array to string
{% highlight csharp %}
Encoding.ASCII.GetString(byteArray, 0, byteArray.Length)
{% endhighlight %}