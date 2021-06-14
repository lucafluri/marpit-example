---
marp: true
# Meta
title: "Presentation Title"
description: "Presi descr"

# Theme
theme: uncover  
style: |
  a:link {
    color: #ff0;
  }
class: invert 
backgroundColor: #121212

paginate: false
header: "**header**"
footer: "footer"

---
<!-- _backgroundColor: yellow -->
<!-- _color: black -->
<!-- _header: "" -->
<!-- _footer: "" -->
# Presentation

Markdown presentation with Marpit!

```bash
$ some commands
```

---
<!-- _color: white -->
## Syntax

![bg blur:5px](https://images.unsplash.com/photo-1425913397330-cf8af2ff40a1?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1934&q=80)
Blurred bg image  
</br>
You can write slides in Markdown

Each slide should be separated with a ---

---

## Lists

![bg vertical right:50%](https://images.unsplash.com/photo-1558710763-9791081edd44?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1951&q=80)

![bg](https://images.unsplash.com/photo-1425913397330-cf8af2ff40a1?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1934&q=80)

1. gfg
2. gdfg
3. gdfgfd

- gfg
- fgd
- gdfg

---

## Formatted text

As Kanye West said:

> We're living the future so
> the present is our past.

This is normal text

This is **bold text**

This is `inline code`

This is a [link](http://www.google.com)

---

## Code blocks

An explanation for the code below:

```python
import os

print(os.getcwd())
```

```python
import shutil

columns, rows = shutil.get_terminal_size()
```

---

# A table

| aaaaa | e | D |
|:-:|-:|-|
| ee | bbb | GDFG |
| ff | d | cccc |

---

## Math
$E = mc^2$
$\frac{1}{2} = \int_{\pi}^{42} x^2 dx$

---
## Images

```
![RC](IMAGELINK LOCAL OR ONLINE)
```

![](https://api.qrserver.com/v1/create-qr-code/?data=https%3A%2F%2Fgithub.com%2Flucafluri%2Fmarpit-example%2Fblob%2Fmaster%2FREADME.md&size=220x220&margin=10)

Add margins to qrcode!

<!-- _backgroundColor: navy -->

---
# h1
## h2
### h3
#### h4
Normal Text

---
## Colored Text

<span style="color:gray;">Gray</span>
<span style="color:yellow;">Yellow</span>
<span style="color:red;">Red</span>

---
## Links

[Marpit example repo](https://github.com/lucafluri/marpit-example)


---
## Colums

<table>
<tr>
<td>

**Column 1**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas hendrerit mattis lobortis. In consequat volutpat enim, non maximus massa pulvinar vel.. 

</td>
<td>

**Column 2**
[Random Link](https://github.com/)
 Donec semper ultricies fermentum. Curabitur accumsan, nibh interdum tristique rutrum, felis felis fringilla urna

</td>
</tr>
</table>


---
<!-- _header: "" -->
<!-- _footer: "Author Name 2021
[author@mail.com](mailto:author@mail.com) 
--
[author.com](http://wwww.author.com)" -->
# End
