# [Markdown](https://en.wikipedia.org/wiki/Markdown) ↔ [Wikitext](https://en.wikipedia.org/wiki/Help:Wikitext)

## Headers

**Markdown**


```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

**Wikitext**

```
=H1=
==H2==
===H3===
====H4====
=====H5=====
======H6======
```

**Output**
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

Markdown | Wikitext | Output
-- | -- | --
`*italics*`<br>`_italics_` | `''italic''` | _italics_
`**bold**`<br>`__bold__` | `'''bold'''` | __bold__
`~~strikethrough~~`<br>`<s>strikethrough</s>` | `<s>strikethrough</s>` | ~~strikethrough~~

## Lists
*(Spaces are indicated with dots: ⋅)*

### Unordered

**Markdown**

```
* One
⋅⋅* One.one
⋅⋅⋅⋅* One.one.one
* Two
* Three
```

or

```
- One
- Two

+ One
+ Two
```

**Wikitext**

```
* One
** One.one
*** One.one.one
* Two
* Three
```

**Output**

* One
  * One.one
    * One.one.one
* Two
* Three

### Ordered

**Markdown**

```
1. One
⋅⋅⋅1. One.one
⋅⋅⋅⋅⋅⋅1. One.one.one
2. Two
3. Three
```

**Wikitext**

```
# One
## One.one
### One.one.one
# Two
# Three
```

**Output**

1. One
   1. One.one
      1. One.one.one
2. Two
3. Three

## Links

Markdown | Wikitext | Output
-- | -- | --
`[Internal link](/README.md)` | `[[/README.md\|Internal link]]` | [Internal link](/README.md)
`[Internal section](/README.md#Links)` | `[[README.md#Links\|Internal section]]` | [Internal section](/README.md#Links)
`[External link](https://www.google.com)` | `[https://www.google.com External link]` | [External link](https://www.google.com)

## Images

Markdown | Wikitext | Output
-- | -- | --
`![Internal image](/github.png)` | `[[File:Github.png\|alt=Internal image]]` | ![Internal image](/github.png)
`![External image](https://raw.githubusercontent.com/khang-nd/markdown-wikitext/main/github.png)` | - | ![External image](https://raw.githubusercontent.com/khang-nd/markdown-wikitext/main/github.png)
`[![Image with link](/github.png)](https://github.com)` | `[[File:Github.png\|link=https://github.com]]` | [![Image with link](/github.png)](https://github.com)

## Inline code

Markdown | Wikitext | Output
-- | -- | --
`` `code` ``<br>`<code>code</code>` | `<code>code</code>` | `code`

## Code blocks and Syntax highlighting

**Markdown**

````
```javascript
var s = "JavaScript syntax highlighting";
console.log(s);
```
````

**Wikitext**

```
<syntaxhighlight lang="javascript">
var s = "JavaScript syntax highlighting";
console.log(s);
</syntaxhighlight>
```

**Output**

```javascript
var s = "JavaScript syntax highlighting";
console.log(s);
```

## Tables

**Markdown**

```
Header 1 | Header 2 | Header 3
--- | --- | ---
Cell 1 | Cell 2 | Cell 3
Cell 4 | Cell 5 | Cell 6
```

**Wikitext**

```
{|
! Header 1 !! Header 2 !! Header 3
|-
| Cell 1 || Cell 2 || Cell 3
|-
| Cell 4 || Cell 5 || Cell 6
|}
```

**Output**

Header 1 | Header 2 | Header 3
--- | --- | ---
Cell 1 | Cell 2 | Cell 3
Cell 4 | Cell 5 | Cell 6

## Block quotes

**Markdown**

```
> Stay hungry, stay foolish
```

**Wikitext**

```
<blockquote>Stay hungry, stay foolish</blockquote>
```

**Output**

> Stay hungry, stay foolish

## Horizontal rules

**Markdown**

`---` or `____` or `***`

**Wikitext**

`----`

**Output**

---
