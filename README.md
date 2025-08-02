### Accessibility NavBar menu
___

### ARIA - Accessible Rich Internet Aplications

#### aria-hidden

aria-hidden="true". Controls that element should not be exposed to accessibility API. Cannot be reached with TAB key.

#### aria-label
aria-label="open sidebar". Describes what the element is doing. What ever we assign to this aria label attribute, would be read outloud by the screen reader technology.

##### If an element is controling an interactive element, it needs more aria attributes.

#### aria-expanded
aria-expanded="false". Explains the default state of element

#### aria-controls
aria-controls="navbar". Explains what element it controls by assigning the elements ID as aria's value.

#### aria-current
aria-current="page". This tells the screen readers that this is the current website.

___

### Focus of elements
##### The focus should not the placed on elements that are not visible.

#### Inert attribute
Inert attribute removes the element from the accessibility tree,
makes it untabbable,
does not hide it visually