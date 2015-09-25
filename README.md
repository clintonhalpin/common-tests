# common-tests

Boilerplate Tests that we should add to every single great web app.

### TOC
1. [Accessibility](#acessibility)
2. [User Authentication](#user-authentication)
3. [Performance](#performance)

### Accessibility

Stolen from [A11yproject Checklist](http://a11yproject.com/checklist.html)

```
# Aria Tests

should have HTML element with role="banner"
should have HTML element with role="navigation"
should have HTML element with role="main"
should have HTML element with role="contentinfo"

# Language

should have language specified on <html> 

# Document Outline

should have title attribute
should have description attribute
links should have :focus state 
links should have :hover state 
links should have :active state
images should have alt text

# Routes

[ routes ] should be accessible by a URL

# Javascript 

should render something without javascript

# Forms

should be able to tab all form elements
should have label for all form controls (e.g. input, select etc.)

# Contrast

should have a suitable contrast

# Devices

should work with a screen reader
should be able to navigate with a keyboard only
```

### User Authentication

```
should log in
should sign up
should log out
should reset password
should refresh token
should create new user
should delete user
should update user
```

### Performance

Stolen from [Google PageSpeed](https://developers.google.com/speed/pagespeed/?hl=en)

```
should Avoid CSS @import
should Avoid a character set in the meta tag
should Avoid bad requests
should Avoid landing page redirects
should Combine images into CSS sprites
should Enable Keep-Alive
should Inline Small CSS
should Inline Small JavaScript
should Minify CSS
should Minify HTML
should Optimize images
should Optimize the order of styles and scripts
should Prefer asynchronous resources
should Put CSS in the document head
should Put JS at the end of the document body
should Serve resources from a consistent URL
should Specify a character set
should Minimize redirects
should Minimize payload 
should Enable compression
should Serve scaled images
should Minimize delay in page load 
should Minimize request size
should Specify image dimensions
should Defer parsing of JavaScript
should Leverage browser caching
should Specify a cache validator
should Remove query strings from static resources
should Specify a Vary: Accept-Encoding header
```
