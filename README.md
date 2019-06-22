# Extend-bootstrap-.container-.col-to-edge-of-viewport-fix

A small bootstrap sass mixin based off the make-container-max-widths() 
mixin to give the effect of one column inside a container extending to 
the edge of the viewport.

No absolute positioning, ::after selector or hacks needed. Simply have 
one .row .no-gutter element and two child .cols. The mixin minuses 
$container-max-width() from 100vw and sets it as the margin either on 
the left or right. As $container-max-width() is set for each breakpoint 
his mixin works across all browser widths and has a max width so it 
works when you need to stack your columns.
