---
marp: true
theme: gaia
---

# Using Marp

* Create a slide deck all in one .md file
* Compile as html or pdf
* Download html locally and open with a browser or host for free with Github Pages, etc for presenting
* Relatively lightweight and easy to use

---

# Some Examples:

Code:

```python

print("hello world")

```

Math:

$$
f_{\vec{w},b}(\vec{x}) = \vec{w} \cdot \vec{x} + b
$$

---

![bg hue-rotate:90deg saturate](background/background.jpg)

# <span style="color: blue;">Choose an Image for the Background</span>

<span style="color: blue;">In case you want a "template" to use besides the two default ones offered</span>

---

# Two Columns (or more)
- Image on one column and text on the other is relatively easy
- Two text columns is much harder


![bg left](images/rubberduck.jpg)

---

# Emoji Support :rocket:

List of Emojis supported at:

https://gist.github.com/rxaviers/7360908


---

# Embedding

Generally, this is not recommended due to script injection.

With the Marp CLI, you will have to pass the argument --html

<iframe width="568" height="322" src="https://www.youtube.com/embed/EzQ-p41wNEE" title="Never use PowerPoint again" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>