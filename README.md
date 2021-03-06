# common-tests

Boilerplate Tests that we should add to every single great web app.

### TOC
1. [Accessibility](#acessibility)
2. [Performance](#performance)
3. [User Authentication](#user-authentication)
4. [Twitter Social Sharing](#twitter-social-sharing)
5. [Facebook Social Sharing](#facebook-social-sharing)
6. [CRUD](#crud)

### Accessibility

Stolen from [A11yproject Checklist](http://a11yproject.com/checklist.html)

```
# Aria Tests
should have HTML element with role="navigation"
should have HTML element with role="main"

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
...routes should be accessible via a URL
...routes.states should be accessible via a URL

# Javascript 
should render something basic without javascript

# Forms
should be able to tab between form elements
should have label for between form controls (e.g. input, select etc.)

# Contrast
should have a suitable contrast

# Devices
should work with a screen reader
```

### Performance

Stolen from [Google PageSpeed](https://developers.google.com/speed/pagespeed/?hl=en)

```
should Avoid CSS @import
should Avoid a character set in the meta tag
should not have bad requests
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

## Features

### User Authentication

```
should log in
should sign up
should log out
should reset password
should refresh [authentication method (token or cookie) ]
should create new user
should delete user
should update user
```

### Twitter Social Sharing

```
should have <meta name="twitter:card" content="summary">
should have <meta name="twitter:site" content="">
should have <meta name="twitter:url" content="">
should have <meta name="twitter:title" content="">
should have <meta name="twitter:description" content="">
should have <meta name="twitter:image" content="">
```

### Facebook Social Sharing

```
should have <meta property="og:title" content="" />
should have <meta property="og:type" content="website" />
should have <meta property="og:url" content="" />
should have <meta property="og:image" content="" />
should have <meta property="og:description" content="" /> 
should have <meta property="og:site_name" content="" />
```

### Crud

```
should create [ RESOURCE ]
should read [ RESOURCE ]
should update [ RESOURCE ]
should delete [ RESOURCE ]
```
