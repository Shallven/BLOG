---
title: Example content
---



### Title

## Title2

# Title3

* * *

## Separateline


- - - - - -

### Link

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

See my [About](/about/) page for details.


### Referencelink

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

### BlockQuote

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

### Code


{% highlight js %}

function trigger_alert(){
  alert("Lorem Ipsum dolor sit amet");
}

trigger_alert();

{% endhighlight %}

using plugin : code

{%code 
function trigger_alert(){
  alert("Lorem Ipsum dolor sit amet");
}
trigger_alert();
%}

### list
unordered list

* Praesent commodo cursus magna.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

ordered list

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus.
3. Maecenas sed diam eget risus.


using <dl>,<dt>,<dd> tags
<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

### Image

![Large example image](http://placekitten.com/g/800/400 "Large example image")
![Medium example image](http://placekitten.com/g/400/200 "Medium example image")
![Small example image](http://placekitten.com/g/200/200 "Small example image")

## table

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Rank</th>
      <th>Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Cookie</td>
      <td>#69</td>
      <td>169</td>
    </tr>
    <tr>
      <td>Buther</td>
      <td>#70</td>
      <td>169</td>
    </tr>
    <tr>
      <td>Stuart</td>
      <td>#71</td>
      <td>168</td>
    </tr>
  </tbody>
</table>

### Video

{% youku XMjY4MTUxMDc0OA 800 400%}

{% youku XMjY4MTUxMDc0OA %}

{% youku XMjY4MTUxMDc0OA 400 200%}
