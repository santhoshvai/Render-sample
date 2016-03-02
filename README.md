# Android Performance - Rendering lesson - sample app

* Visualize and Fix Overdraw
  * Nullified the window background
  * Removed unnecessary backgrounds from xml markup
  * Display a background color only if there is no avatar image

* Fixing Overdraw with Canvas API
  * `clipRect` performs geometric restricts while drawing cards so that overdraw is restricted when cards are stacked.

* Optimizing your layout
  * Using a flattened layout hierarchy
  * linearLayout with nested views is replaced with a relativeLayout
  * using a hierarchy viewer we can see that the linearLayout performs poorly compared to the relativeLayout
