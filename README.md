# Embedding Images And Video | The Odin Project

This is the repo for the Embedding Images And Video project in the HTML And CSS course of The Odin Project

## What I Learned

Recreating a YouTube video page was very enlightening.  This was an exercise not necessarily on how to embed images and videos but on how to organize the HTML such that the content organization is integrated with the styling organization.  There are a lot of parts that make up the page and each part in itself is made of many other smaller parts.  A lot of thought has to be given to the design of the structure so that everything looks good and long-term maintenance is easy.

### Sematic HTML

I tried to use as much semantic HTML as possible, avoiding using `<div>` elements as much as possible.  I feel HTML5 made huge strides in making elements more defined, not only for purposing but also for accessibility.  And the generic `<div>` element is still available for those purposes that cannot be used by another element.  I implemented `<section>` and `<article>` a lot more than usual.  The two are still a little vague to me, but they do explain a lot more about the element than a `<div>` which has now been repurposed as a styling division.

### Only Using External CSS

There were so many one-off elements that I would have loved to just put in some inline styling, but I held myself back and put it all on the external stylesheet.  While my personal projects have been a mix of internal and external CSS, this convention is not good for long-term maintenance because changes would be hard to debug having to look at all possible sources.  Separation of concerns is key to good maintenance.

### CSS Reset

I typically don't use a CSS reset but I gave it a try on this project.  While it's nice that the CSS reset gives a clean styling slate and eliminates the most common inconsistencies between browsers, I think it might be too clean.  I found myself a bit lost figuring out if a property should be listed under a common element, a class, or an ID.  Maybe I have gotten used to having the default browser formatting, but aside from the margins and padding I'm not sure if there is a need for a full-blown styling reset unless the content is so specialized it needs it.