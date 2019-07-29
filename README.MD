# HTML CSS TWO

In this lesson we cover HTML and CSS topics such as:
- position properties
- display properties
- flex box

## Position

The `position` property is used to specify the position of an element on the screen.

There are five main values we can give this property:

`static` - this is the default value for an element, and it tells the element to render in order with the document flow.

`relative` - this will tell the element to render relative to it's normal position in the document flow.

`absolute` - this will position an element relative with the nearest positioned ancestor. If there is not an ancestor, it will use the document body

`fixed` - this will position the element relative to the view port. This means that the element will always be displayed to our screen.

`sticky` - this will position an element based on the usersw scroll position. It toggles between fixed and relative. It will be relative until it hits a scroll position threshold then become fixed. 