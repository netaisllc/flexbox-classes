# flexbox-classes
Simplest-ever CSS classes for flexbox based layout with notes willfully copied
from [MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes) pages.
Class names are loosely based on the [SUIT CSS](https://github.com/suitcss/suit/blob/master/doc/README.md)
naming convention, but purists may have concerns.

## Is the flexbox model confusing?
No, not really.  But when you're just starting to use it, the similarity of terms
can be an impediment to getting your head around it.

## Are there learning resources out there?
Absolutely. Many, many good ones exist including MDN. Just google.

## Then why?
Easy. When you are old-school, it helps to go through each property and option
and see how it fits into the big picture.  Then it made sense to 'document'
some things in a LESS file that I could use on projects.

### Things that could be better emphasized in tutorials

##### Flexbox containers and flexbox items.
These are two different roles that any item (element) may serve in the context
of the flexbox model.  A _flexbox-container_ is simply an element that lays out
its children using the model.  A _flexbox-item_ is simply a child on a flexbox-container.

Of course, other flexbox properties can be applied to either the parent and/or the
children to impact their display behavior.

 In some cases, an element will serves one role, in other cases, it may serve the
 other role. And there is nothing that prevents an element from being both a
 container and item at the same time.

##### Flexbox properties relate to only one role.
The CSS properties that comprise the flexbox model are relevant to one and
only one "role" in the sense I'm using above. For example, the property **align-items**
only makes sense in the realm of _flex-containers_ while the property **align-self** only
makes sense in the realm of _flex-items_.

On the interwebs, I found many tutorials that descrine them in a sort of all-together style.
Not sure why this is, and I should point out that not everybody does this. For example, [CSS-Tricks' guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) makes the distinction very well. I just find the layout of the info hard to work with.

## Should I use this?
Seriously -- you're asking?
