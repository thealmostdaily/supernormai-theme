---
title: To-do
layout: page
---

# Todo

<p class="red">
I'm mixing theme with site structure.  <br>
This is not good.   <br>
Need to separate.   
</p>

So…  
Build pages but don't worry about the liquid code for now. The aim is to style everything and get the page structure correct.  

- [ ] see notes for pages types and build the type I need eg.:

- [x] Build a page with a Work on it
- [ ] A work archive / overview / list page (grid with lazy load, 8 - 12 items)
- [ ] Build a single exhibition page
- [ ] Build an exhibition archive / list / overview page
- [ ] A journal single post page
- [ ] A journal archive page
- [ ] Build an about page

and style accordingly.

Build the structure for the site with content in supernormal-site or supernormal-structure or supernormal-skeleton

OR

I can build the structure etc into the theme but need to stop and a MVP point so can then keep the theme ready as a base for other sites.



## Links
- fix links across all pages  
- see if styles can be added inline as per poster site.


[A link in the body text](http://cnn.com)


## Navigation
- fix page order in nav bar: works \| exhib \| writing/journal \| about
    - manually enter code
    - write liquid so can order pages by adding order number to yaml?

- exclude "home" from menu "if else?"


## notes
Default Layout is like a container for the other layouts.
single-work slots into the the {{ content }} container. By not including content styles in the default layout (other than that in <main> ) all page specific styles are held in the page itself. This allows for greater flexibiliy of layouts all with the frame of the default page. 
