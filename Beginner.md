# Table of Contents

- [Table of Contents](#table-of-contents)
- [1. Headings](#1-headings)
- [Heading 1](#heading-1)
  - [Heading 2](#heading-2)
    - [Heading 3](#heading-3)
      - [Heading 4](#heading-4)
        - [Heading 5](#heading-5)
          - [Heading 6](#heading-6)
- [2. Paragraphs](#2-paragraphs)
- [3. Line breaks](#3-line-breaks)
- [4. Emphasis](#4-emphasis)
  - [Bold](#bold)
  - [Italicized](#italicized)
  - [Bold and Italicized](#bold-and-italicized)
- [5. Blockquotes](#5-blockquotes)
  - [Multiple Paragraphs](#multiple-paragraphs)
  - [Nested Blockquotes](#nested-blockquotes)
  - [Blockquotes with Other Elements](#blockquotes-with-other-elements)
- [6. Lists](#6-lists)
  - [Ordered](#ordered)
  - [Alternative Syntax (using the same number)](#alternative-syntax-using-the-same-number)
  - [Unordered](#unordered)
  - [Starting Unordered List Items With Numbers](#starting-unordered-list-items-with-numbers)
  - [Adding Elements in Lists](#adding-elements-in-lists)
    - [Paragraph](#paragraph)
    - [Images](#images)
- [7 Code](#7-code)
  - [Escaping Backticks](#escaping-backticks)
  - [Code Blocks](#code-blocks)
  - [Syntax Highlighting](#syntax-highlighting)
- [8. Horizontal Rules](#8-horizontal-rules)
- [9. Links](#9-links)
  - [Adding Titles](#adding-titles)
  - [URLs and Email Addresses](#urls-and-email-addresses)
  - [Formatting Links](#formatting-links)
  - [Footer Links](#footer-links)
- [10. Images](#10-images)
  - [Adding links to images (buttons)](#adding-links-to-images-buttons)
- [11. Characters You Can Escape](#11-characters-you-can-escape)
- [12. HTML](#12-html)
- [13. Tables](#13-tables)

# 1. Headings

There are 6 different heading levels

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

```md
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

Alternative syntax

```md
# Heading level 1

## Heading level 2
```

# 2. Paragraphs

There is no special syntax for plain text.

This is a sentence.

```md
This is a sentence.
```

# 3. Line breaks

Add two spaces at the end of a line to create a line break.

This is  
a line break

```md
This is  
a line break
```

# 4. Emphasis

## Bold

I just love **bold text**.

```md
I just love **bold text**.
```

## Italicized

Italicized text is the _cat's meow_.

```md
Italicized text is the _cat's meow_.
```

## Bold and Italicized

This is really **_very_** important text.

```md
This is really **_very_** important text.
```

# 5. Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.

```md
> Dorothy followed her through many of the beautiful rooms in her castle.
```

## Multiple Paragraphs

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

```md
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

## Nested Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

```md
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

## Blockquotes with Other Elements

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>   _Everything_ is going according to **plan**.

```md
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>   _Everything_ is going according to **plan**.
```

# 6. Lists

## Ordered

1. First item
2. Second item
3. Third item
4. Fourth item

```md
1. First item
2. Second item
3. Third item
4. Fourth item
```

1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
4. Fourth item

```md
1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
4. Fourth item
```

## Alternative Syntax (using the same number)

1. First item
1. Second item
1. Third item
1. Fourth item

```md
1. First item
1. Second item
1. Third item
1. Fourth item
```

## Unordered

- First item
- Second item
- Third item
- Fourth item

```md
- First item
- Second item
- Third item
- Fourth item
```

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

```md
- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item
```

## Starting Unordered List Items With Numbers

- 1968\. A great year!
- I think 1969 was second best.

```md
- 1968\. A great year!
- I think 1969 was second best.
```

## Adding Elements in Lists

### Paragraph

- This is the first list item.
- Here's the second list item.

  I need to add another paragraph below the second list item.

- And here's the third list item.

```md
- This is the first list item.
- Here's the second list item.

  I need to add another paragraph below the second list item.

- And here's the third list item.
```

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

```md
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
```

### Images

1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

   ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.

```md
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

   ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
```

# 7 Code

At the command prompt, type `nano`.

```md
At the command prompt, type `nano`.
```

## Escaping Backticks

``` Use `code` in your Markdown file. ```

```md
``` Use `code` in your Markdown file. ```
```

## Code Blocks

To create code blocks, indent every line of the block by at least four spaces or one tab.

    <html>
      <head>
      </head>
    </html>

```md
    <html>
      <head>
      </head>
    </html>
```

or use tripple back ticks

```md
Like this
```

    ```md
    Like this
    ```

## Syntax Highlighting

Add the name of the language or abbreviation after the opening tripple back ticks

```py
print("Hello world!")
```

    ```py
    print("Hello world!")
    ```

# 8. Horizontal Rules

These create horizontal seperation bars in the document.

---

Separate

---

Sections

---

```md
---
Seperate
---

Sections

---
```

# 9. Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

```md
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

## Adding Titles

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com 'The best search engine for privacy').

## URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>  
<fake@example.com>

```md
<https://www.markdownguide.org>  
<fake@example.com>
```

## Formatting Links

I love supporting the **[EFF](https://eff.org)**.
This is the _[Markdown Guide](https://www.markdownguide.org)_.
See the section on [`code`](#code).

```md
I love supporting the **[EFF](https://eff.org)**.
This is the _[Markdown Guide](https://www.markdownguide.org)_.
See the section on [`code`](#code).
```

## Footer Links

To create a footer with text links just add the `•` between the links.

[Website](#) • [Email Updates](#) • [Forum](#) • [Meetups](#) • [Youtube](#) • [Twitter](#) • [Facebook](#) • [Contact Us](#)

```md
[Website](#) • [Email Updates](#) • [Forum](#) • [Meetups](#) • [Youtube](#) • [Twitter](#) • [Facebook](#) • [Contact Us](#)
```

# 10. Images

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg 'San Juan Mountains')

```md
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg 'San Juan Mountains')
```

## Adding links to images (buttons)

[![Google Icon](/assets/images/google.png 'Search on Google.com')](https://google.com)

```md
[![Google Icon](/assets/images/google.png 'Search on Google.com')](https://google.com)
```

# 11. Characters You Can Escape

| Character | Name                                           |
| --------- | ---------------------------------------------- |
| \\        | backslash                                      |
| \`        | backtick (see also escaping backticks in code) |
| \*        | asterisk                                       |
| \_        | underscore                                     |
| \{ }      | curly braces                                   |
| \[ ]      | brackets                                       |
| \< >      | angle brackets                                 |
| \( )      | parentheses                                    |
| \#        | pound sign                                     |
| \+        | plus sign                                      |
| \-        | minus sign (hyphen)                            |
| \.        | dot                                            |
| \!        | exclamation mark                               |
| \|        | pipe (see also escaping pipe in tables)        |

# 12. HTML

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

This <strong>word</strong> is bold. This <em>word</em> is italic.

```md
This <strong>word</strong> is bold. This <em>word</em> is italic.
```

# 13. Tables

Tables are created by having a title row, a formatting row, and content rows. The first row is the title row, containing the column names. The next row states how the content shoul be aligned, having colons `:` on the left of the dashes `-` will align everything to the left, same with the right. To center the content, add a colon on each side of the dashes.

| Tables | Are | Annoying | To  | Type  |
| :----- | :-- | :------- | :-- | :---- |
| 1      | 2   | 3        | 4   | 5     |
| foo    | bar | baz      | qux | lorem |
| 5      | 4   | 3        | 2   | 1     |

```md
| Tables | Are | Annoying | To  | Type  |
| :----- | :-- | :------- | :-- | :---- |
| 1      | 2   | 3        | 4   | 5     |
| foo    | bar | baz      | qux | lorem |
| 5      | 4   | 3        | 2   | 1     |
```

| Tables | Are | Annoying | To  | Type  |
| :----: | :-: | :------: | :-: | :---: |
|   1    |  2  |    3     |  4  |   5   |
|  foo   | bar |   baz    | qux | lorem |
|   5    |  4  |    3     |  2  |   1   |

```md
| Tables | Are | Annoying | To  | Type  |
| :----: | :-: | :------: | :-: | :---: |
|   1    |  2  |    3     |  4  |   5   |
|  foo   | bar |   baz    | qux | lorem |
|   5    |  4  |    3     |  2  |   1   |
```

Typing out talbes is also very annoying, so I suggest using a table generator such as <https://www.tablesgenerator.com/markdown_tables>.
