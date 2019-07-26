This is a little xonsh script I've been putting together to split up
pages in a PDF that were scanned as duplex, where there are two pages
side by side on each page of the PDF. I'm sure it needs many more
options and refinements but for the moment it can handle a few things.

* Split pages that are in numerical order
* Split pages that were scanned with staples removed
* Reassemble weird PDFs where the page image is made of multiple little images
* Run [noteshrink](https://github.com/mzucker/noteshrink.git) on scanned images to reduce their size
* Run jbig2 on scanned images to convert them to tiny 1bit images

