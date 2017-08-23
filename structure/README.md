# Lesson 1: Structuring HTML

## Page Structure

In their simplest form, webpages are simply digital representations of any other page that you might have read. Newspaper or magazine articles, shopping catalogues, and even insurance forms can be represented in webpages.

## Content Structure

Within each page, the content should also maintain a certain structure to make it understandable to the viewer. An article might have varying headings to break up the content to make it more readable, a catalog will usually make good use of images to promote products for sale, and an insurance form might group related fields together.

## Structuring a Page in HTML

### Elements

HTML is made up of elements that represent the content that is contained within them. Each element will begin and end with an angle bracket. The characters within the brackets indicate the element's purpose.

> Most elements follow a pattern of opening tag, content, closing tag.

Here is a paragraph element. You can tell the difference between a closing tag and an opening tag by the forward slash `/` preceding the element name.

```html
<p>HTML is awesome!</p>
```

And here is an image element, which only has one tag. This is considered a self-closing tag.

```html
<img src="http://myawesomesite.com/images/some-image.jpg" />
```

### Root Element

Before you can write any HTML elements in your html document, however, you have to let the browser know to expect HTML. You accomplish this with an opening and closing `<html>` tag. The `<html>` element is the top-level element that all other HTML markup is contained in. It is referred to as the "root element" for this reason.

### Body Element

The `<body>` element will contain all of the content of the webpage. For this reason, it too must have both an opening and a closing tag.

Here is a basic example of the root and body elements of a web page.

```html
<html>
	<body>
		<!-- content will go here -->
	</body>
</html>
```