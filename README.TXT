This template operates as a single-file web application built with vanilla HTML, CSS, and JavaScript. It runs entirely on the client side without requiring any backend configuration.

How the background system and image management work:

* **Automatic Image Detection**
The script automatically checks for background image files in the root directory upon loading. It begins searching from `fond.jpeg` for the primary view, then sequentially scans for `fond2.jpeg`, `fond3.jpeg`, and so on, until no further numbered files are found.
* **Dynamic Page Backgrounds**
The site maintains three distinct visual views. Each view remembers its own active background and allows users to cycle through all detected background files independently using the navigation buttons on the interface.
* **Contextual Emojis**
The falling emoji animations adapt automatically to whichever background image is currently active, matching predefined sets of icons associated with each specific image file.
