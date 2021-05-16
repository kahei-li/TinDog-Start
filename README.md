# TinDog Starting Files
Forked from Londonappbrewery github.
Adding bootstrap notes here:

# Notes on bootstrap
- bunch of frontend code created by twitter that can be reusable by others.
  - includes lots of pre-styled elements
  - the default elements are all already formatted and with lots of css classes ready to use
- download bootstrap code getbootstrap.com
- how to install bootstrap to our site
  - use link element to reference a bootstrap CDN, typically alreeady or will be cached by users
  - download the bootstrap source code to your site directory, may have latency for user when first access

## Wireframing your site
- Wireframing - Quick simple site to determine design direction and ideas
- Mock-up an almost final design for the site
- prototype animation to present site mock-ups

## Bootstrap notes II
- navbar
  -ul / li
- background color nav bar
- navbar-brand
- ml-auto (adding margin left to the element)
- toggler (hamburger menu - condenses navbar into a menu button when screen size changes)
  - order matters e.g. collapsible button and brand line (determine left or right for each.)
- fixed position (navbar will remain even when scrolling
- bootstrap grid system
  -row class
  -col class (max=12)
    - class="col-md-6" #anything medium size (pad) or larger will take 6/12. Smaller size (phone) will take 12/12
    - col-lg (large) laptop or large screen
- corousel
  - slides function for testimonials and reviews. with dynamic switch buttons.
- card and card deck
  - card / with row arrangements for pricing and options
- stacking
  - positioning and z-index to stack elements
- fine tuning bootstrap grid / responsive designs / CSS breakpoints
  -media query
    - can change CSS base on set conditions
    - @media <type> <feature>
