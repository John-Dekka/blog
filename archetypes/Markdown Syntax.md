This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also it shows whether basic HTML elements are decorated with CSS in a Hugo theme.

## Headings[](https://hugo-terminal.vercel.app/posts/markdown-syntax#headings)

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h1)

## H2[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h2)

### H3[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h3)

#### H4[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h4)

##### H5[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h5)

###### H6[](https://hugo-terminal.vercel.app/posts/markdown-syntax#h6)

## Paragraph[](https://hugo-terminal.vercel.app/posts/markdown-syntax#paragraph)

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes[](https://hugo-terminal.vercel.app/posts/markdown-syntax#blockquotes)

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution[](https://hugo-terminal.vercel.app/posts/markdown-syntax#blockquote-without-attribution)

> Tiam, ad mint andaepu dandae nostion secatur sequo quae. **Note** that you can use _Markdown syntax_ within a blockquote.

#### Blockquote with attribution[](https://hugo-terminal.vercel.app/posts/markdown-syntax#blockquote-with-attribution)

> Don’t communicate by sharing memory, share memory by communicating. — Rob Pike[1](https://hugo-terminal.vercel.app/posts/markdown-syntax#fn:1)

## Tables[](https://hugo-terminal.vercel.app/posts/markdown-syntax#tables)

Tables aren’t part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

|Name|Age|
|-|-|
|Bob|27|
|Alice|23|

#### Inline Markdown within tables[](https://hugo-terminal.vercel.app/posts/markdown-syntax#inline-markdown-within-tables)

|Italics|Bold|Code|
|-|-|-|
|_italics_|**bold**|`code`|

## Code Blocks[](https://hugo-terminal.vercel.app/posts/markdown-syntax#code-blocks)

#### Code block with backticks[](https://hugo-terminal.vercel.app/posts/markdown-syntax#code-block-with-backticks)

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block indented with four spaces[](https://hugo-terminal.vercel.app/posts/markdown-syntax#code-block-indented-with-four-spaces)

```
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block with Hugo’s internal highlight shortcode[](https://hugo-terminal.vercel.app/posts/markdown-syntax#code-block-with-hugos-internal-highlight-shortcode)

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

## List Types[](https://hugo-terminal.vercel.app/posts/markdown-syntax#list-types)

#### Ordered List[](https://hugo-terminal.vercel.app/posts/markdown-syntax#ordered-list)

1.  First item
2.  Second item
3.  Third item

#### Unordered List[](https://hugo-terminal.vercel.app/posts/markdown-syntax#unordered-list)

-   List item
-   Another item
-   And another item

#### Nested list[](https://hugo-terminal.vercel.app/posts/markdown-syntax#nested-list)

-   Fruit
    -   Apple
    -   Orange
    -   Banana
-   Dairy
    -   Milk
    -   Cheese

## Other Elements — abbr, sub, sup, kbd, mark[](https://hugo-terminal.vercel.app/posts/markdown-syntax#other-elements--abbr-sub-sup-kbd-mark)

GIF is a bitmap image format.

H2O

Xn + Yn = Zn

Press CTRL+ALT+Delete to end the session.

Most salamanders are nocturnal, and hunt for insects, worms, and other small creatures.

---

1.  The above quote is excerpted from Rob Pike’s [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015. [↩︎](https://hugo-terminal.vercel.app/posts/markdown-syntax#fnref:1)