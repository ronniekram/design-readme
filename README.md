# For My Design Friends 🥰

You can find a page with all of the lesson elements here.
* On the initial page, you will be able to choose a color theme. 
* There will be buttons that allow you to click through elements. 
* There are notes/known bugs/etc for lesson elements below.
* There also might be some questions in the list below. Whomst knows?
* Elements on page will be ordered to match the list below.
* Notes in **bold** are known issues related to design.
* Notes in *italics* are known issues with libarries or functionality.

**Currently not included**: Hotspot, Polling, Scale Slider

## --- New & Redesigned Elements ---

### Input List
  * With media, no background image
  * Without media, background image
  * ~*Submit button still disabled when all fields are filled.*~
  * ~*Input field "lights" not changing when field is updated.*~

### Text Input
  * With media, no background image
  * Without media, background image
  * ~*Submit button still disabled when all fields are filled.*~

### Visual Multiple Choice
  * ~*Lightbox not closing with button, but clicking outside the picture will close it.*~
  * One selection, no background image, two columns
  * Multiple selections, background image, three columns

### Multiple Choice
  * With media, one selection, question aligned center.
  * Without media, multiple selections, question aligned left.

### Chapter Breaker/Title
  * Custom colors, left aligned
  * Themed colors, right aligned
  * Background, button, text and button text colors are customizable in this element.
  * All colors will default to theme if no custom colors are used in the builder.
  * Content can be left or right aligned.
  * ~*Need to update this to have the same hex validation functionality that Category Choice buttons have.*~

### Matching Drag and Drop
  * Placeholder animation is a little bit goofy.
  * ~*Currently, when a card is removed from left side, the cards below it move up one place. I am working on a fix.*~
  * ~*Sometimes the movable card disappears into the void.*~

### Ordered Drag and Drop
  * Placeholder animation is a little bit goofy.
  * ~*Currently, when a card is removed from left side, the cards below it move up one place. I am working on a fix.*~
  * ~*Sometimes the movable card disappears into the void.*~

### Lesson Summary
  * **The assignment row at the end of the summary needs to be replaced.**
  * ~*The modal close button needs to be clicked twice in order to close.*~ **Fixed on a different branch**
  * ~*Ran into issues with the rating library I used, so it is not displayed on the rating tab of the feedback modal at the moment.*~
  * With skips
  * Without skips

### Protected Or Not
  * Lottie is currently ***not implemented***.

## --- Legacy Elements ---
### All legacy element widths were changed to match the new/updated element widths.

### Matrix
  * **Q-Bone:** Should theme colors apply to this element as well? If so, how should they be applied?

### Image Comparison
  * Right side label is showing even when the image is minimized. I think I need to fiddle with z-index on this.

### Multiple Choice Comparison
  * One selection
  * Multiple selections

### Student Upload
  * This literally does not do anything right now.

### Media Switcher
  * Selected tab has an opacity of 50%.

### News Judge
  * **Q-Bone:** Tablet view sizing-- In legacy elements, there was no difference in size on the sliders for desktop and tablet. They look kind of bulky here though.
  * ~*All sliders are currently starting at a value of 10, need to adjust this to start at no value.*~

### Category Choice (formerly Infozone)
  * Button colors will be customizable for this element, but will default to theme colors if custom is not specified.
  * This element has a function that validates hex codes. If an invalid hex is entered, button will fall back to theme colors.

### Passive
  * Media title is left aligned here.
  * Headings are center aligned here.

