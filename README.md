# odin-admin-dashboard
Utilizing CSS Grid and Flexbox to showcase a design layout for an admin dashboard from The Odin Project. Project description here:  https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard

I wanted to take a moment to mention something important I discovered while doing this
project. Even though my grid layouts looked pretty nice between both my desktop with 
its own monitor resolution and my laptop with its own resolution, I noticed that the 
output display looks quite different between both devices.

The font-family looks different despite using the same platform (xubuntu) and the sizes 
and spacing also look different when using certain units. I think I am beginning to see the
importance of using proper units when developing a page so that the layout and format looks
similar across devices. 

I have primarily been using px for most of the sizing, but since I am seeing how much of a 
difference the display looks between devices, I am going off on my own way to study best
practices for unit application. First up is this YouTube video, and I will follow up with some notes: https://www.youtube.com/watch?v=wKLXXE3Tq_c

* Pixels are useful for things like: 
    - Icon sizes
    - margins
    - paddings
    - width and radius portions of borders
    - container widths

*  Pretty sure you know this one, but percentages are based on parent sizes.