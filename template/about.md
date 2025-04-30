---
layout: inner
title: About
permalink: /about/
---
## Markdown

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](/index.html).

There should be whitespace between paragraphs.

# About

Brandin Moore is a programmer and photographer from Brooklyn, New York, that enjoys combining tech with creativity. Coming from an urban environment, Brandin enjoys visually capturing the stories of different environments, scenarios, and communities. As a programmer, he enjoys creative coding and creating accessible and secure technologies. As a part of a group course project in February 2025, he designed the backend for [FocusBloom](https://github.com/bensim0305/FocusBloom), a task scheduling application intended for students with ADHD. He also created a digital sampler, which was used in a group musical composition.

In his photography, he has worked with multiple organizations in capturing the visions of creative and professional storytelling. In May 2024, he worked with the University of Chicago’s Major Activities Board to photograph concert photos for their premier concert, Summer Breeze. These photos were later published in Firebird Magazine’s 2025 issue, the University’s only music publication. He has also worked with the Visuals Series at UChicago, bringing the stories of Black creatives to life. 

At his core, Brandin is passionate about community, storytelling, and exploration. He graduates from the University of Chicago with a Bachelor of Science in Computer Science in June 2025, and completion of the Media Arts and Design minor program.


## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

{% highlight js %}
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
{% endhighlight %}

{% highlight ruby %}
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
{% endhighlight %}

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

---

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Wide image

![Branching](https://guides.github.com/activities/hello-world/branching.png)

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

{% highlight txt %}
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
{% endhighlight %}

{% highlight txt %}
The final element.
{% endhighlight %}

---

## Syntax highlighting

Jekyll has [built in support](https://jekyllrb.com/docs/templates/#code-snippet-highlighting) for syntax highlighting of over 60 languages thanks to [Rouge](http://rouge.jneen.net/).

To render a code block with syntax highlighting, surround your code as follows:

{% highlight markdown %}
{% raw %}
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}
{% endraw %}
{% endhighlight %}

[Pygments](http://pygments.org/) styles are present under section 6.0 of `css/style.scss` for customization.

### Examples

---

#### Bash

{% highlight bash %}
>_ ssh -i ~/.ssh/id_rsa account@host.com
account@host:~$
$ var="my-value"
$ echo $var
my-value
$ logout
{% endhighlight %}

#### HTML

{% highlight html %}
<!DOCTYPE html>
<html>
 <head>
   <meta charset="UTF-8">
   <title>title</title>
 </head>
 <body>

 </body>
</html>
{% endhighlight %}

#### CSS

{% highlight css %}
/*--------------------------------------------------------------
	1.0 Defaults
--------------------------------------------------------------*/

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}

body {
  background-color: #e9edf0;
  @extend %opensans;
  -webkit-font-smoothing: antialiased;
}
{% endhighlight %}

#### YAML

{% highlight yaml %}
### Phantom settings
paginate: 10
footer_text: '© 2018 Jami Gibbs'
admin_name: 'Jami Gibbs'
google_analytics: "UA-9999999-99" # Update with your own tracking ID

#### Phantom Navigation menu
enable_nav: true
nav_item:
  - { url: '/', text: 'Home' }
  - { url: '/about', text: 'About' }
{% endhighlight %}
