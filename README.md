# Lightbox2 #

## PixelAgency changes ##

Changes:

* Option to show videos and/or iframe video (such as youtube/vimeo).

## Example ##

You need to set the fields `kind` and `size`. The `kind` can be `image`, `video` or `iframe`.
The href in this case will be the video URL.
The size instead is used to have a specific size for the lightbox, so it should be of the same resolution as the video/iframe.
If showing an image you can skip this fields.

```php
<a href="<?= $url ?>" data-lightbox="gallery" data-kind="<?= $kind ?>" data-size="<?= $image ?>">
  <img data-src="<?= $thumb ?>" alt="<?= $alt ?>">
</a>
```

### Note ###
This version in based on 2.11.4 that includes a few changes in naming.
I've also added a SCSS file since that's what we use.

## Original README ##

The _original_ lightbox script.

Lightbox is small javascript library used to overlay images on top of the current page. It's a snap to setup and works on all modern browsers.

- **Demos and usage instructions.** Visit the [Lightbox homepage](http://lokeshdhakar.com/projects/lightbox2/) to see examples, info on getting started, script options, how to get help, and more.
- **Releases and Changelog**. Viewable on the [Github Releases page](https://github.com/lokesh/lightbox2/releases)
- **Roadmap.** View the [Roadmap](https://github.com/lokesh/lightbox2/blob/master/ROADMAP.md) for a peek at what is being planned for future releases.
- **License.** Lightbox is licensed under the MIT License. [Learn more about the license.](http://lokeshdhakar.com/projects/lightbox2/#license)

by [Lokesh Dhakar](http://www.lokeshdhakar.com)
