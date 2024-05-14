# Paragraph

By default everything is a paragraph

to seperate two different para we put an extra blank line in between

to create an actual line break  
we put two space at the end of the previous line

# Headings

to create headings we can use hash

### the more hashes we put the smaller the headings (upto 6)

# Typography

code: `double asterics for **bold**`  
output: double asterics for **bold**

code: `single underscore for _italic_`  
output: single underscore for _italic_

code: `**_this is bold and italic_**`  
output: **_this is bold and italic_**

code: `this is ~~strike through~~`  
outptut: this is ~~strike through~~

code `this is <mark>highlighted text</mark>`  
output: this is <mark>highlighted text</mark>

code: `x<sup>2</sup>`  
output: superscript: x<sup>2</sup>

code: `x<sub>2</sub>`  
subscript: x<sub>2</sub>

emoji: just put an emoji 👍

# Code

### Single line code

Put backticks for single line code  
`Console.log('single line code');`

### Multi line code

Put 3 backticks for multiline code

```js
const a = [1, 2, 3];

for (let i = 0; i < a.length; i++) {
    console.log(a[i]);
}

// also does syntax highlighting and format

console.log('done');
```

# Creating a link

[This is a link](https://www.google.com)  
<https://www.google.com>

```markdown
[This is a link](https://www.google.com)

<https://www.google.com>
```

# Inserting image

### Code:

`![Google Logo](image_address)`

### Demo:

![Google Logo](https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png)

# Blocked quote

> this is a quote  
> abcd
>
> > double nesting
> >
> > > triple nesting

# Horizontal rule

Line1

---

Line2

# List

### Ordered list

#### Code:

```markdown
1. item1
2. item2
3. item3
```

#### Output:

1. item1
2. item2
3. item3

### Unordered list

#### Code:

```markdown
-   item1
-   item2
    -   item3
    -   item4
```

#### Output:

-   item1
-   item2
    -   item3
    -   item4

# Table

### Code:

```markdown
| column1 | column2 | column3 |
| :------ | :-----: | ------: |
| a       |    b    |       c |
| x       |    y    |       z |
```

### Output:

| column1 | column2 | column3 |
| :------ | :-----: | ------: |
| a       |    b    |       c |
| x       |    y    |       z |
