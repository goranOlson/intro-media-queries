# Intro Media Queries

### What is media queries?
Media queris in CSS are a way to applay styles to a web page based on the size on the give screen. We can have a rather large screen, and we can alson have a very small one, like a mobile phone. This is very useful for creating responsive web pbag designs that adapt to different screens and devices.

How do we do this? Of course by using media queries.

Here is a basic example: 
```css
@media screen and (max-width: 600px) {
    /* Styles for screens with a maximum width of 600 px*/
    nav {
        background-color: red;
    }
}
```
- `@media`: this is the keyword that indicates the beginning of a media query.
- `screen`: specifies that styles within the media query should only apply to devices with sceens (not devices that might not have screen, like printers).
- `(max-width: 600px)`: this is the condition that must be true in order for the styles within the media query to be applied. In this case, the styles will only apply id the screen width is 600px or less.

There ar many more ways you can specify your condition, but in the majority of cases we use `max-width` or something that is called `min-width`.


