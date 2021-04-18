# How Markdown works.
Markdown, is well, interesting. It has some things from a normal text file, like this, but with `#`, that can change. Here is a table that shows what everything looks like, sort of equivalent to `html` headers.

| #'s        | HTML Equivalent |
| ---------- | --------------- |
| #          | h1 (biggest)    |
| ##         | h2              |
| ###        | h3              |
| ####       | h4              |
| #####      | h5              |
| ######     | h6 (smallest)   |

Here is all of the sizes with their `h` number except from `1` and `2`

### h3
#### h4
##### h5
###### h6

I'd recommend looking through this file with an editor such as VS Code to see how the items actually work/are triggered

Here is an example of how `h6 (######)` can be used and also includes a link:
###### Created by [Oscie](https://oscie.tk)

This is how a list works: 
- Literally just use dashes
- It's as easy as that

## Formatting
Basically, you can use different things to format text (a bit like html again), and here is how it works

| Symbols         | How it looks |
| --------------- | ------------ |
| \*abc\*         | *abc*        |
| \*\*abc\*\*     | **abc**      |
| \*\*\*abc\*\*\* | ***abc***    |
| \_abc\_         | _abc_        |
| \_\_abc\_\_     | __abc__      |
| \`abc\`         | `abc`        |
| \~\~abc\~\~     | ~~abc~~      |
| \=\=abc\=\=     | ==abc==      |

## Images and Links

Links are simple, just like this:

`[Oscie](https://oscie.tk)` - [Oscie](https://oscie.tk)

Images are similar, but different

`![Ryaltopia](https://oscie.tk/assets/ryaltopia.png)` - ![Ryaltopia](https://oscie.tk/assets/ryaltopia.png)

In the link's case, the word(s) inside the `[]` are what you click, however for images the word(s) inside the `[]` acts as alt-text, so when the image cannot be loaded.

## Deeper into Lists

Indents (or 4 spaces) allow what I call "sub-lists", where you can have an item within its own list

You can always use the normal dashes
- Just like this
    - Or this if you want

Or you can use `*`
* Like I am now
    * This also works

For some reason, `+` also works
+ See this,
    + Interesting, right?

You can also have numbered lists

1. Like this
2. You cant have the same thing as the others tho (no `2.2` or anything)

## Quotes
Basically, it adds a thin line to the start of the line and Indents it to however many `>`'s you put

> This is with one `>`

> You can do multiple as long as you seperate it with a line
>> This is how 2 look like

>> 2 at a time do this when seperated

## Horizontal line breaks and code snippets
Three dashes `---` create a line

---
Thats how it looks, just a normal line I guess

### Code Snippets
An indent or 4 spaces, will make a large code block

    Like this, its in its own block
Then there are also the `inline code snippets` as you've seen before

## References
In markdown, there is a way to create references, like this
**Ryaltopia is a [mod][1] for Miitopia**

[1]: https://oscie.tk/ryaltopia "Oscie: Ryaltopia"

### Behind the scenes
    **Ryaltopia [mod][1] for Miitopia**
    [1]: https://oscie.tk/ryaltopia "Oscie: Ryaltopia"

The bold isn't needed, but it just looks nicer in my opinion

## Escaping and `HTML`
In markdown, you can escape formatting and stuff like that using `\` before the symbol, so:

*hi* with `\` before the `*`'s would be `\*hi\*` or \*hi\*

### `HTML`
Another cool feature about markdown is that you can embed HTML inside of it, here is an example

<button>Button</button>

Weird thing about these, is you cannot put them in an `inline code block`, large code block or escape it entirely. You can, though, format the text in the button:

<button>***`Button`***</button>

It just uses the same formatting methods that markdown usually uses

## Advanced markdown
Here is the stuff that is too small to have its own category

### Automatic Links
`https://oscie.tk`

https://oscie.tk

### Footnotes

The quick brown fox[^1] jumped over the lazy dog[^2].

## Final thoughts
Welp, thats the basics of markdown. Theres surely many other things I have missed out but any of those shouldnt be needed. Thanks for reading to the end!

[^1]: Foxes are red
[^2]: Dogs are usually not red
