# Intro to Markdown

## What is Markdown??

Markdown is a markup language that was developed by John Gruber in 2004. It allows you to add formatting to a plaintext document so that you could publish it on the internet as-is without adversely affecting the readability of the markup file by including html tags and other formatting instructions. Markdown syntax is made from regular punctuation characters, all of which were chosen to look like what they mean when reading a markdown file.  

## Let's Learn Some Basics

The best way to practice markdown is to write some. First, open your preferred text editor and create a markdown file (remember that the file extension for markdown is .md, so you'll want to call your file something like YOUR-TITLE.md). Next, we're going to recreate this page -- the one you're reading right now -- using markdown. So far, we've used Header 1, Header 2, and some regular plain text. Some useful resources/links are [this](https://www.markdownguide.org/cheat-sheet/) markdown cheat sheet and [this](https://daringfireball.net/projects/markdown/syntax) more detailed explainer by markdown creator John Gruber. Let's get started!

### Paragraphs and In-Line Text Elements

Paragraphs don't require and special markdown syntax and can be written as plaintext.

We can hit "Enter" and start a new paragraph down here. We can also use markdown syntax to make part of our text **bold** or to *italicize* it. If you want to cross out some of your text, you can use ~~strikethrough~~ syntax.

### Blockquote

If you have text you want to make stand out:

> Turn it into a blockquote like this to set it apart from your other text.

### Lists

You can put the steps to a process in an ordered list:

1. Do this first.
2. Then this.
3. Then this.

Or put some bullet points in an unordered list:

- Like this.
- And this.
- And this.

Sometimes, you might want to create a task list with check boxes:

- [ ] Do this.
- [ ] Then this.
- [ ] Then this.

Note that, depending on what you're using to read your markdown file, you might be able to check off each task list item as you complete it.

If you want to create a list of defined terms you can use a definition list:

Term
: words that define the term.

Another term
: and another definition

### Writing Code in Markdown

You may find yourself needing to display code in markdown, especially if you're a programmer or a technical writer. You can write code in-line with your text, take `console.log("Hello World")`, for example, or you can set it off using a code block, like this:

```
function sayHi(name) {
  console.log("Hello, ", name);
};

sayHi("Saima");
```

### Linking to external sites

We already practiced linking to other sites when we linked to the [markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) above. However, we can also link to and display images, like this picture we found online at https://cdn.shopify.com/s/files/1/1788/4235/files/PPF-BlogUpdate-Thumbs_0041_42_Cat-Stages.jpg:

![picture of a cat](https://cdn.shopify.com/s/files/1/1788/4235/files/PPF-BlogUpdate-Thumbs_0041_42_Cat-Stages.jpg)

### Tables

You can also organize information in markdown using a table, like this:

| Name | Age |
| ---------- | ---------- |
| Tiny Buttons | 6 |
| Charlie | 1 |

## Great Job!