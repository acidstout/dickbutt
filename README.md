# Dickbutt Bookmarklet
This will plaster a website with randomly sized and positioned dickbutts. Uses an inline SVG image in order to eliminate external references.

# Usage
Create a new bookmark in your browser with the content of the dickbutt.min.js file as URL and prepend 'javascript:' as protocol. Click the newly created bookmark on any website to have it plastered with dickbutts.

# Known issues
* Due to the nature of adding multiple elements to the DOM this will become noticably slower if the number of dickbutts is increased.
* Some browsers limit the maximum length of URLs in bookmarks (e.g., 10,000 chars in Chromium based browsers), so the possibilities in the code even if minified are very limited.
* On dark pages the dickbutts will be hardly visible. Adding an outline to the image, bloats it to \~12KB which is too much for browsers. Reducing the filesize down to \~6KB, which should perfectly fit. However, inline images seem to be truncated after \~4KB of data resulting in the SVG not being rendered. So, if you really feel the urge of having dickbutts all over dark pages, just add a fill attribute with your desired color to the paths in the SVG.
* This breaks your Google Remote Desktop session if used in the window where the session is being run. Just reload the session to make it work again.