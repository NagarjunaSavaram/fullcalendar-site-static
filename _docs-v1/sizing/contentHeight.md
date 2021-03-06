---
title: contentHeight
since_version: 1.4.2
---

Will make the calendar's content area a pixel height.

<div class='spec' markdown='1'>
Integer
</div>

By default, this option is unset and the calendar's height is calculated by [aspectRatio](aspectRatio).

Example usage of `contentHeight`:

```js
$('#calendar').fullCalendar({
  contentHeight: 600
});
```

## Setter

You can dynamically set a calendar's contentHeight after initialization:

```js
$('#calendar').fullCalendar('option', 'contentHeight', 650);
```
