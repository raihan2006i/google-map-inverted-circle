### How to draw Inverse Circle in Google Map?

In Google Map Javascript API the regular Circle has an option to fill the inside of circle with a color, but there is no option to fill the outside of the circle. After lots of searching in Google and reading Google Map Javascript API, when I didn't find any solution, then I started to build my own library to draw an InvertedCircle. I used google.maps.MVCObject class to give same functionality as regular Circle of  Google Map Javascript API

It has following methods and events

| Methods  | Return Value | Description
| -------- | ------------ | ----------- 
| getBounds() | LatLngBounds | Gets the LatLngBounds of this Circle.
| getCenter() | LatLng | Returns the center of this circle.
| getEditable() | boolean | Returns whether this circle can be edited by the user.
| getMap() | Map | Returns the map on which this circle is displayed.
| getRadius() | number | Returns the radius of this circle (in meters).
| getVisible() | boolean | Returns whether this circle is visible on the map.
| setCenter(center:LatLng) | None | Sets the center of this circle.
| setEditable(editable:boolean) | None | If set to true, the user can edit this circle by dragging the control points shown at the center and around the circumference of the circle.
| setMap(map:Map) | None | Renders the circle on the specified map. If map is set to null, the circle will be removed.
| setRadius(radius:number) | None | Sets the radius of this circle (in meters).
| setVisible(visible:boolean) | None | Hides this circle if set to false.

| Events  | Arguments  | Description
| -------- | ------------ | ----------- 
| center_changed  | None  | This event is fired when the circle's center is changed.
| radius_changed  | None  | This event is fired when the circle's radius is changed.
| visible_changed  | None  | This event is fired when the circle's visible is changed.

Here is the screenshots of InvertedCircle

![Inverted Circle on Google Map](http://4.bp.blogspot.com/--mczRhxY_NM/UR_XNVE3_hI/AAAAAAAAAH4/bYOZ7zNZm4c/s1600/inverted-circle.png)

For example check demo folder
