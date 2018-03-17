# jQuery Sticky Element plugin

This is a simple jQuery plugin I developed and used on client projects at White Lion Interactive.

## Functionality

Sticky styling can be applied to an element by calling:

```
$('.my-sticky-element').sticky();
```

The plugin accepts an options object to allow configuration of:

* `breakpoint` - the device width at which the sticky functionality should be disabled
* `offset` - the distance from the top of the window at which sticky should start
* `stopper` - an element below the sticky element in the DOM where the element should stop sticking

At a minimum the component requires a trigger (a button or anchor element with `[data-modal-show="some-modal"]`) and a modal (an element with `[data-modal="some-modal"]`). The modal dialog is responsive and uses flexbox for positioning, so it may be easily centered, if desired.

_Note: This repo is for code review (read-only) purposes. The component relies on dependencies that are not not included in this project._
