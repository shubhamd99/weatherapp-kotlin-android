### Weather App in Kotlin

##### Notes:

1. Relative Layout - RelativeLayout is a view group that displays child views in relative positions. The position of each view can be specified as relative to sibling elements (such as to the left-of or below another view) or in positions relative to the parent RelativeLayout area (such as aligned to the bottom, left or center). A RelativeLayout is a very powerful utility for designing a user interface because it can eliminate nested view groups and keep your layout hierarchy flat, which improves performance. 

![relative_layout](https://developer.android.com/images/ui/relativelayout.png)

2. Linear Layout - LinearLayout is a view group that aligns all children in a single direction, vertically or horizontally. You can specify the layout direction with the android:orientation attribute.

3. What is the difference between Android units of measure?

a) px - Pixels - corresponds to actual pixels on the screen.
b) in - Inches - based on the physical size of the screen. (1 Inch = 2.54 centimeters)
c) mm - Millimeters - based on the physical size of the screen.
d) pt - Points - 1/72 of an inch based on the physical size of the screen.
e) dp or dip - Density-independent Pixels - an abstract unit that is based on the physical density of the screen. These units are relative to a 160 dpi screen, so one dp is one pixel on a 160 dpi screen. The ratio of dp-to-pixel will change with the screen density, but not necessarily in direct proportion. Note: The compiler accepts both "dip" and "dp", though "dp" is more consistent with "sp".
f) sp -  Scaleable Pixels OR scale-independent pixels - this is like the dp unit, but it is also scaled by the user's font size preference. It is recommended you use this unit when specifying font sizes, so they will be adjusted for both the screen density and user's preference. Note, the Android documentation is inconsistent on what sp actually stands for, one doc says "scale-independent pixels", the other says "scaleable pixels".
