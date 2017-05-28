---
layout: page
#<link rel="stylesheet" href="/sass/_functions.scss">
title: "A Responsive eNewsletter"
subheadline: "One eNewsletter, Many Devices"
teaser: "Employees have access to many devices. A responsive decision will allow them to view eNewsletter content however they choose."
breadcrumb: true
categories:
    - Blog
tags:
    - Communication Deliverable
    - Communication Deliverable Newsletter
header:
    title: The Communication Blog
    background-color: "#EFC94C;"
    image_fullwidth: 03com2000.jpg
    caption: Photo by Startup Stock Photos - @estrattonbailey & @wearesculpt.
    caption_url: http://startupstockphotos.com/

image:
    title: b03co_1660_title.jpg
    thumb: b03co_1660_thumb.jpg
    homepage: b03co_1660_home.jpg
    caption: Photo by @lumvox - Unsplash.
    caption_url: https://unsplash.com/@lumvox
---
<!--more-->

## Creating a Responsive eNewsletter
Explain philosophy and content, source of template etc...

### eNewsletter Responsive Design 01
<!-- Sample 2-->
<!-- Posts panel container -->
<div class="posts-panel grid">

  <!-- Panel's header -->
  <header class="panel-header">
    <h1 class="panel-title">Featured Posts (Grid)</h1>
  </header>

  <!-- Panel's content -->
  <div class="panel-content">

    <!-- Pinned post section -->
    <section class="pinned-post">
      <!-- Post item -->

      <div class="post-item">

        <!-- Post's thumbnail -->
        <a href="#" class="post-thumbnail">
          <img src="https://static.pexels.com/photos/24587/pexels-photo-24587.jpg" alt="">
        </a>

        <!-- Post's text -->
        <div class="post-text">

          <!-- Post's title -->
          <a href="#">
            <h3 class="post-title">Post title place-holder</h3>
          </a>
          <div class="post-meta">
            <span class="meta"><span class="meta-icon fa fa-user-circle-o" aria-hidden="true"></span><a class="meta-text">Steve Jobs</a></span>
            <span class="meta"><span class="meta-icon fa fa-clock-o" aria-hidden="true"></span><span class="meta-text">22/06/2030</span></span>
          </div>

          <!-- Post's summary -->
          <div class="post-summary">
            <p>Your work is going to fill a large part of your life, and the only way to be truly satisfied is to do what you believe is great work. And the only way to do great work is to love what you do. If you haven't found it yet, keep looking. Don't settle. As with all matters of the heart, you'll know when you find it....
              <a href="#" class="post-read-more">Read more<span class="fa fa-chevron-circle-right" aria-hidden="true"></span></a>
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Posts list -->
    <section class="posts-list">
      <div class="post-item">
        <a href="#" class="post-thumbnail">
          <img src="https://static.pexels.com/photos/66274/sunset-poppy-backlight-66274.jpeg" alt="">
        </a>
        <div class="post-text">
          <a href="#">
            <h3 class="post-title">Post title place-holder</h3>
          </a>
          <div class="post-meta">
            <span class="meta"><span class="meta-icon fa fa-user-circle-o" aria-hidden="true"></span><a class="meta-text">Steve Jobs</a></span>
            <span class="meta"><span class="meta-icon fa fa-clock-o" aria-hidden="true"></span><span class="meta-text">22/06/2030</span></span>
          </div>
        </div>
      </div>

      <div class="post-item">
        <a href="#" class="post-thumbnail">
          <img src="https://static.pexels.com/photos/33109/fall-autumn-red-season.jpg" alt="">
        </a>
        <div class="post-text">
          <a href="#">
            <h3 class="post-title">Post title place-holder</h3>
          </a>
          <div class="post-meta">
            <span class="meta"><span class="meta-icon fa fa-user-circle-o" aria-hidden="true"></span><a class="meta-text">Steve Jobs</a></span>
            <span class="meta"><span class="meta-icon fa fa-clock-o" aria-hidden="true"></span><span class="meta-text">22/06/2030</span></span>
          </div>
        </div>
      </div>

      <div class="post-item">
        <a href="#" class="post-thumbnail">
          <img src="https://static.pexels.com/photos/12567/photo-1444703686981-a3abbc4d4fe3.jpeg" alt="">
        </a>
        <div class="post-text">
          <a href="#">
            <h3 class="post-title">Post title place-holder</h3>
          </a>
          <div class="post-meta">
            <span class="meta"><span class="meta-icon fa fa-user-circle-o" aria-hidden="true"></span><a class="meta-text">Steve Jobs</a></span>
            <span class="meta"><span class="meta-icon fa fa-clock-o" aria-hidden="true"></span><span class="meta-text">22/06/2030</span></span>
          </div>
        </div>
      </div>

      <div class="post-item">
        <a href="#" class="post-thumbnail">
          <img src="https://static.pexels.com/photos/370018/pexels-photo-370018.jpeg" alt="">
        </a>
        <div class="post-text">
          <a href="#">
            <h3 class="post-title">Post title place-holder</h3>
          </a>
          <div class="post-meta">
            <span class="meta"><span class="meta-icon fa fa-user-circle-o" aria-hidden="true"></span><a class="meta-text">Steve Jobs</a></span>
            <span class="meta"><span class="meta-icon fa fa-clock-o" aria-hidden="true"></span><span class="meta-text">22/06/2030</span></span>
          </div>
        </div>
      </div>
    </section>
  </div>
</div>


### eNewsletter Responsive Design 02

/// Defatul bottom margin of the panel
/// @type List
$panel-margin: rem-calc(20 10);
/// Default background color of the panel
/// @type Color
$panel-container-background-color: $white !default;

/// Default radius of the panel
/// @type List
$panel-container-radius: $global-radius !default;

/// Default bottom border width of the panel's header
/// @type Number
$panel-header-border-bottom-width: rem-calc(4) !default;

/// Default bottom border color of the panel's header
/// @type Color
$panel-header-border-bottom-color: $light-gray !default;

/// Default font color of the panel's title
/// @type Color
$panel-header-color: $dark-gray;

/// Default font size of the panel's title
/// @type Number
$panel-header-font-size: rem-calc(26) !default;

/// Default bottom border color of the post
/// @type Color
$post-item-border-bottom-color: $light-gray !default;

/// Default bottom border width of the post
/// @type Number
$post-item-border-bottom-width: rem-calc(1) !default;

/// Adds styles for post-list's elements in small screen and it also could be used for bigger screen in small areas
@mixin small-posts-list {
  .posts-list{
    .post-title{
      font-size: rem-calc(18);
    }

    .post-meta{
      font-size: rem-calc(12);
    }

    .post-summary{
      font-size: rem-calc(12);
    }
    .post-read-more{
      display: none;
    }
  }
}


.posts-panel{
  @include grid-col-row();
  float: none !important;
  margin: $panel-margin;
  background-color: $panel-container-background-color;
  border-radius: $panel-container-radius;
  box-shadow: rem-calc(0 0 4 0) rgba(0,0,0,.2);

  .panel-header{
    @include grid-col-row();
    border-bottom: $panel-header-border-bottom-width solid $panel-header-border-bottom-color;

    .panel-title{
      margin: 0;
      padding: rem-calc(15 0);
      color: $panel-header-color;
      font-size: $panel-header-font-size;
    }
  }

  .panel-content{
    padding: rem-calc(15 0);
  }

  .pinned-post, .posts-list{
    @include grid-col-row($gutters: 0);
  }

  .posts-list{
    .post-item:not(:last-child){
      border-bottom: $post-item-border-bottom-width solid $post-item-border-bottom-color;
    }
  }

  .post-item{
    @include grid-row();
    padding: rem-calc(15 0);

    .post-thumbnail{
      display: block;
      @include grid-column($columns: 4);

      img{
        width: 100%;
        height: auto;
      }
    }

    .post-text{
      @include grid-column($columns: 8);

      p{
        margin: 0;
      }
    }
    .post-title{
      font-size: rem-calc(26);
    }
    .post-meta{
      color: $dark-gray;
      font-size: rem-calc(14);
    }
    .meta{
      display: inline-block;
      margin-#{$global-right}: rem-calc(15);
    }
    .meta-icon, .meta-text{
      display: inline-block;
      padding-#{$global-right}: rem-calc(5);
    }

    .post-summary{

    }

    .post-read-more{
      display: block;
      font-size: rem-calc(14);

      .fa{
        padding: rem-calc(0 5)
      }
    }
  }

  .pinned-post{
    .post-item{
      border-bottom: $post-item-border-bottom-width solid $post-item-border-bottom-color;
    }
    .post-thumbnail{
      display: block;
      @include grid-col-row();
      img{
        width: 100%;
        height: auto;
      }
    }

    .post-text{
      @include grid-col-row();
      margin-top: rem-calc(15);
    }
  }

  @include breakpoint(small only){
    @include small-posts-list;
  }

  @include breakpoint(medium only){
    .posts-list{
      .post-title{
        font-size: rem-calc(20);
      }

      .post-meta{
        font-size: rem-calc(14);
      }

      .post-summary{
        font-size: rem-calc(14);
      }
    }
  }

  // Grid styles
  &.grid{
    .pinned-post, .posts-list{
      @include grid-column($columns: 6, $gutters: 0);

      @include breakpoint(small only){
        @include grid-col-row($gutters: 0);
      }
    }

    .pinned-post{
      .post-item{
        border: 0;
      }
    }

    @include small-posts-list;
  }
}




### More Communication Posts
{: .t60 }

{% include list-posts tag='Communication Deliverable' %}
