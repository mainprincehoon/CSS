## Suggestions to Organize Your CSS

-- Follow Your Team

-- Use comments to create headers 

-- Sort properties alphabetically ABCSS

-- Larger projects follow a naming convention methodology. For example: BEM - Block (normally defined), Element ( __ ), Modifier (--)   (these are not rules but it's good to follow them)


-- When naming classes in HTML/CSS, we usually use simple names like header -button. However, when we want to add a modifier to a class, we use two hyphens (e.g., button--border) instead of one, to clearly indicate that it is a modifier. This helps other developers understand the structure more easily. Apart from modifiers, we can also create elements within a block using two underscores, like header__button, where button is a part of the header block. This follows the BEM (Block Element Modifier) naming convention. We can also apply multiple modifiers to a single class by adding them with spaces. In this case, I've used header-button because the button is inside a block whose class is named header, so calling it header-button makes it clear and organized. If someone else looks at the code, they'll immediately understand that the button belongs to the header section.
