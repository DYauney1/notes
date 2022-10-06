---
id: asmldg9eu54vgc6hvpzxqja
title: MarkDown
desc: ''
updated: 1665025273439
created: 1665023864142
---
I intend to document (as well as just try out) the different features of Dendron's markdown formatting. This where it'll happen.

## Basics

First off, I want to try out the things I've already heard of. I got the gist of what's possible in markdown from [MarkDown Guide][1] and it was this website that inspired me to get a markdown editor in the first place.

### Linking

That link up there, for example, was made using a markdown feature (and frankly one I'm really happy I have access to): Reference Linking. It's where the URL for a link is defined in a different place in the file from the hyperlinked text. It looks like this:

```
[linking information][1]

Random other text (not important)

[1]: reference.url
```

Truth be told, I'm not positive I'm really a fan of the formatting used in that code snippet. I used triple backticks before and after the code (you'll find the same feature on [stackoverflow][2]) and I've tried this on a few other editors before this. Theirs looked cleaner. 

Other ways to create a link include simply typing out the url: https://google.com (that was turned into a link automatically) as well as [doing something like this](https://abc.xyz) (which involves the display text being typed in brackets, followed by the url in parentheses).

### The other type of linking

This is something I saw [online][3] and I haven't tried it out yet. I'm very excited to do so.

It's making a link (recognized in the Dendron tree) to another page. It might look [[MarkDown.Like This]].  
I'm actually a little surprised that worked. I made a new file, titled it `like this` and made the link. Everything just connected.[^1]

It seems to me that every folder in Dendron is really just a page. You *could* try to make a folder without a page, but it would be very confusing and ultimately inefficient. 

## What's next?

I've got a handle on most of the features, I think:
- Lists are possible
    - Alongside sub-lists

- [ ] Checkboxes can be created
- [x] ...And subsequently filled.

> Quotes can be written  
> as large as you'd like  
> and ***formatting*** included within them

---
Dividers can be inserted with trivial ease  
and the distinction between new-lines and paragraphs is evident

I've been told that :emojis: can be added, tables can be made, and definitions can be created, but I haven't found how they work just yet.

The next step for me is probably to commit this to GitHub, and configure a page for it. After all, much of the purpose of this format is for me to be able to share my notes with others in an effective, meaningful, and yes, impressive, way. 






[^1]: I'm actually really excited to see what else I can do with linking. There's a panel in Dendron dedicated to visualizing the different linkages, and it has the potential to be very complex and nuanced (a feature I like in a new long-term tool).


[1]: https://markdownguide.com
[2]: https://stackoverflow.com
[3]: https://wiki.dendron.so/notes/8hwz4bvyy556frx9y04c1cv/

