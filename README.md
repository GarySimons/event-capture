## Event Capture, Propagation, Bubbling and Once

This lesson uses three nested divs of coloured boxes, with a click event listener added.

When either box was clicked it captured all of them. 

When the stopPropagation function was used on the click event, it only captured each individual box. This stopped the 'bubbling' which is when it captures all of them.

Adding once to an event makes it so it only happens once, then 'unbinds' the event (removes it). So that event will only ever happen once. This is useful on a shopping site to stop a 'buy button' being clickec more than once.

