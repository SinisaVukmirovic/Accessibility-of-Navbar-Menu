### Accessibility NavBar menu
___

### ARIA - Accessible Rich Internet Aplications

#### aria-hidden

aria-hidden="true". Controls that element should not be exposed to accessibility API. Cannot be reached with TAB key.

#### aria-label
aria-label="open sidebar". Discranet what the element is doing. What ever we assign to this aria label attribute, would be read outloud by the screen reader technology.

##### If an element is controling an interactive element, it need more aria attributes.

#### aria-expanded
aria-expanded="false". Explains the default state of element

#### aria-controls
aria-controls="navbar". Explains what element it controls by assigning the elements ID as aria's value.