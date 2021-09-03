# Zipwhip Widget

This is a very simple example of how to embed the Zipwhip Widget on a web page. It includes two examples:

- Embedding the widget in an iframe on the page.
- A button that opens the widget in a new window.

<a href="https://johnchaffee.github.io/zipwhip-widget/" target="_blank">View a live demo &rarr;</a>

## How to add a Texting Widget to your CRM

Zipwhip provides a simple and powerful way to integrate two-way conversational text messaging into any app with a single line of code. The Zipwhip Texting Widget is essentially a miniaturized version of Zipwhip’s text messaging web app that can be embedded in a CRM or workflow app to enable two-way conversational texting. 

## The Widget iframe

The Zipwhip Widget is implemented as an iframe, making integration a breeze.

You can display the widget embedded on a page by adding the sample code below as an iframe.

```html
<iframe
  src="https://embed.zipwhip.com"
  width="400px"
  height="600px"
  frameborder="0"
>
</iframe>
```

Or you can open the widget in a popup window by wrapping it in a `javascript:window.open` link.

```html
<a
  href="javascript:window.open(
  'https://embed.zipwhip.com', 
  '_blank', 
  'width=400px, height=600px, top=100, left=50'
  )"
>
```

You can do a lot more with the Widget, such as locking it to a specific conversation, showing or hiding certain components, and more.

- <a href="https://developers.zipwhip.com/widget/" target="_blank">Learn more on the Zipwhip Developer Portal &rarr;</a>
- <a href="https://johnchaffee.github.io/zipwhip-widget/" target="_blank">View a live demo &rarr;</a>
- <a href="https://github.com/johnchaffee/zipwhip-widget" target="_blank">View the Github repo &rarr;</a>
