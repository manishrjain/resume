+++
# Project title.
title = "FlickrFS"

# Date this page was created.
date = 2005-10-27T00:00:00

# Project summary to display on homepage.
summary = "Virtual filesystem for Flickr"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Filesystem", "Flickr"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fas", icon="globe", name="Original Site", url = "https://sites.google.com/site/manishrjain/flickrfs"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Created FlickrFS which mounts Flickr as a partition in Linux. It was widely
appreciated and featured by [*Wired*](https://www.wired.com/) and
[*Lifehacker*](https://lifehacker.com/mount-flickr-as-a-drive-with-flickrfs-381763).

#### About

Flickrfs is a virtual filesystem which mounts on your linux machine like any other partition. Once mounted, it retrieves information about your photos hosted on your flickr account, and shows them as files. You can now easily copy photos from your local machine to this mount, and it will automatically upload them to your flickr account. Similary, you can copy the files from your mount to your local machine, and it will download your images from flickr.
