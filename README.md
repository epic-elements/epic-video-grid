# \<epic-video-grid\>

## Summary
A grid of videos whose featured video, when clicked on, propagates up to the parent element. Designed to be used in conjunction with <epic-video-player>.

Each video supports a URL, a title, a description, and optionally a thumbnail. If a thumbnail is not provided, this element will dynamically get one from youtube.

Github: https://github.com/epic-elements/epic-video-grid
Author: Alex Goodwin (https://github.com/AlexGoodwin)

## NOTES
There is a bug in IE when a user clicks on the SVG play arrow for videos, it doesn't work. This is due to an IE bug where SVG elements don't support element.classList. Since IE usage is so low, I'm leaving this and moving on.

Dynamic Vimeo thumbnails are currently supported. For now, a URL to a blue 480x360px image with "Vimeo" text is returned.

## TODO
fix vimeo thumbnail support

Further documentation can be found by running `polymer serve` locally, then visiting the components page provided.
