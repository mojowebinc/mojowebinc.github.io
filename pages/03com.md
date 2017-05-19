---
layout: default
format: blog-index
noindex: true
header:
    title: Communication
    background-color: "#EFC94C;"
#    pattern: pattern_concrete.jpg
    image_fullwidth: 03com1600.jpg
    caption: This is a caption for the header image with link
    caption_url: https://unsplash.com/
permalink: "/03com/"

---
<!--more-->



<div class="row">
	<div class="medium-8 columns t30">
		{% include _pagination.html %}
    
    ## Front Matter Code
    ~~~
    header:
        title: header with text
        image_fullwidth: unsplash_brooklyn-bridge_header.jpg
        caption: This is a caption for the header image with link
        caption_url: https://unsplash.com/
    ~~~

	</div><!-- /.medium-7.columns -->


	<div class="medium-4 columns t30">
		{% include _sidebar.html %}
	</div><!-- /.medium-5.columns -->
</div><!-- /.row -->
