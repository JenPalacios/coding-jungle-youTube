# Everything You Need to Know About HTML

### Disclaimer

This document is meant to give you a holistic view and provide you with the vocabulary you need in case you want to dig deeper into a subject related to HTML.

This is a general outline, you never stop learning anything in development. Even I, who have been coding websites for 5 years, have learned something new during my research for his content.

So take this just as a blueprint, or roadmap to help you out in your learning journey.

Let's start.

## How to write HTML

- What is a tag, and how it looks like
- Block vs inline elements
- How to format text: bold, highlight, italic, subscript, and superscript
- Attributes, and how they are used
- HTML tags: [All HTML Tags](https://www.w3schools.com/tags/default.asp)
- What are semantic tags and why they are important.

![Semantic Tags][semantic_tags]

[semantic_tags]: ./assets/semantic_tags.jpg

[image from w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp)

## Undersand the structure

Below is a snippet of the very basics an HTML page should have to render correctly in the browser.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>EVERYTHING YOU SEE GOES IN HERE</h1>
  </body>
</html>
```

Other things that you need to know regarding the structure:

### Document type

What is `<!DOCTYPE html>` and why it's important to include it

### Head

Important for:

- SEO
- Viewport (responsive)
- Favicon
- Open Graph Meta Tags: Information to show a snippet of the website when sharing on social media or chats. For example, when sharing Coding Jungle's YouTube channel, the snippet looks like this:

![Sharing URLs][share_url]

[share_url]: ./assets/sharing_example.jpg

### Where to link assets

It is important that you understand the pros and cons of linking files in the `<head>` vs at the end of the `<body>` tags.

## Accessibility

- Add `alt` text to images: `<img src='someSource' alt='YOUR alternate text goes here'>`
- Use semantic tags
- Declare languages
  More recomendations from w3
  https://www.w3schools.com/html/html_accessibility.asp

## Security

- Implications of opening in new tab. Use `rel='noopener noreferrer'`
