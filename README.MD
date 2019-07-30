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

## Display

The `display` property is what is used to specify the display behavour of the element.

The values we can give the display preoperty are:

`block` - A block-level element always starts on a new line and takes up the full width available.

`inline` - An inline element does not start on a new line and only takes up as much width as necessary. This will not allow you to modify the height and width.

`inline-block` - Works just like inline, but we can modify the height and width.

`flex` - This will declare the element to be a flex container and use flex box tools for child elements.

`none` - This is used to hide or show an element without actually deleting them.

Example:
![Display Values](images/displays.png)

## Flex Box

Flex box is a tool in CSS that we can use to create a layout, align items, and distribute white space inside of a container. We will apply the `display: flex` to the parent container, and then use that flex container to manipulate the layout for the children elements inside.

We can use `flex properties` to help create this.

Flex Properties:

`flex-direction` - this will determine the axis of how to align items placed inside of the container (vertical or horizontal)
    * row
    * column

`flex-wrap` - by default, flex items will try to sit on the same line so we can tell the overflowed items to wrap to the next line
    * wrap
    * no-wrap
    * wrap-reverse

`justify-content` - this determine how much space to put between each flex item
    * space-around
    * space-between
    * flex-start
    * flex-end
    * center
    * space-evenly

`align-items` - this defines the behaviour for how flex items are laid out along the axis
    * center
    * left
    * right
    * flex-start
    * flex-end

`align-self` - this can be used on a flex item to determine it's own alignment to override the one set by align items
    * same values as align-items

`align-content` - this can be used to mutate the distribution of space between flex items
    * same values as justify-content


## Overflow