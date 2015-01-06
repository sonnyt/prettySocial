prettySocial
============

jQuery prettySocial - a custom share buttons for Pinterest, Twitter, Facebook and Google Plus.

# Setup
Setup is pretty straight forward, each button requires set of `data-*=""` attributes and you apply jQuery plugin.

```JS
	$('.prettySocial').prettySocial();
```

### General
These data attributes applied to all social networks.

Field | Description
--- | ---
`type` | Social Network (twitter, pinterest, facebook, googleplus)
`url` | URL you want to share or current window URL if not defined
`description` | Description of the page
`media` | URL to an image

### Twitter

Field | Description
--- | ---
`via` | Your Twitter screen name

### Facebook

Field | Description
--- | ---
`title` | Your page title

### Generic share

You can add your own share url using in the following scheme and previously
described boiler plates:

    http://example.com/share.php?url={{url}}&title={{title}}
