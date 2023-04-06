<h1 class= "green"> Markdown Cheat Sheet </h1>

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements.

<h2 class= "green"> Basic Syntax </h2>

### Heading

<code class="info"> # H1 </code>
# H1

<code class="info"> ## H2 </code>
## H2

<code class="info"> ### H3 </code> <br>
<p> H3 <p>

<code class="info"> **bold text** </code> ->  **bold text**

<code class="info"> *italicized text* </code> -> *italicized text*

<code class="info"> `code` </code> -> `my code`

<br>

<code class="info"> blockquote: </code>
> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Horizontal Rule

---

### Link
[Markdown Guide](https://www.markdownguide.org)

### Image
![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

<br>Alignment

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

<br>

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


### Strikethrough

~~The world is flat.~~

### Task List
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji
That is so funny! :joy:

### Highlight
I need to highlight these ==very important words==.

### Subscript
`H<sub>2</sub>O` -> H<sub>2</sub>O <br>
ou <br>
`H~2~O` 

### Superscript
`X<sup>2</sup>` -> X<sup>2</sup> <br>
ou <br>
X^2^ <br>

## Using html and css
```
<style>
.red {color: red}
</style>
```
<p class="red">red text</p>

```
h3 {
  color: green
}

blockquote {
 margin: 0;
 border-left: 3px solid #FFF;
}
blockquote p {
 padding: 15px;
 background: #000;
 border-radius: 5px;
}
</style>
```

<!-- my style -->
<style>
  
.green {color: green}
.red {color: red}
.blue {color: #4ED0FB}

code.info {
  color: #4ED0FB
}

h3 {
  color: green
}

</style>