fundify-child
=============

This is a child-theme of the original Fundify, to tune some templates for the coopfunding.net project.

- header.php
- 
its a hard coded tuning of the header.

- footer.php
- 
its to show only the 'legal terms' (linking pages with the meta 'legal') and the 'get stats' div.

- front-page.php
- 
this adds the markup for the slider jquery plugin 'carouFredSel', using the same thumbnails generated by the theme, at 360x222 px each (exactly the size wanted for the 'featured image' of each campaign). Now it links the script from a js folder inside the child theme.

- single-campaign.php
- 
this changes some templating markups ('project-details', 'meta' and 'share'), from the 'content' div to the 'sidebar' div. Also it eliminates the starting big 'featured image' from the main content and only shows the video if it is set.
The 'featured image' of each campaign must be 360x222 px to fit good in the carousel.

- campaign/project-details.php
- 
just to hide the video and the image from this template, because now it shows in the sidebar. The video is showing big and good (if set) in the main-content div, at single-campaign.php

- shortcode-login.php
- 
only to force the redirect of the login to coopfunding.net, because it was going to the same login page... Will try to do it via 'hooks'...

- shortcode-submit.php
-
only adds some buttons to the tinymce wp-editor (image, format), in the frontend campaign submit. Will try to do it via 'hooks'...

- style.css
- 
is the collection of css changes to render the coopfunding.net site

- content-campaign-sort.php
-
is just to add a multilanguage hook in the first item of the campaign categories dropdown ('All')

- inactive.php
-
is a new page-template to list all inactive campaigns, both success and unsuccess...

