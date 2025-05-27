# BOX MODEL 
box model how elements are displayed on a webpage and how they are sized
can be seen rectangular box (border, space inside and outside of it)

# PADDING
Padding is invisible space around the content, inside of the element

# MARGIN
Empty space outside of the between element

-- FILL AREA --
fill with background color or background image
if don't declare width and height in box model it's will be implied by content

defer is best practice in script tag

-- INLINE & BLOCK -- 
# WIDTH
BLOCK with width 100% parent's width element
INLINE width depends on content

# LINE BREAK
BLOCK the element before and after line break

-- WIDTH AND HEIGHT element can be modified in BLOCK
-- Padding and margin in inline top and bottom with INLINE

# CSS LAYOUT
Float makes height parent element = 0;
Float where's director it was floated?

# RESPONSIVE
- View port
- MediaQuery
Mobile-First (Highly Recommend) VS Desktop-First
min-width                           

Start project with padding: 0 and margin: 0
Collapsing margin if 2 elements has the same margin its value will be the same
Adding space between element use margin-bottom also want to margin vertically Inline

# WIDTH
If we set Percentage value for width it depdents on parent element
The child element cannot be larger than parent element
Heading element helps optimize SEO Only H1
Section can have UI Element

2 types of Params: Path Param and query param
Select element with id with anchor tag will navigate to this element

# Table and Forms in HTML
- Position:
+ static is default
+ Relative position will be relative with its first element
+ Absolute will be depend on its parent element relative. If not find any relative then depend on body
+ Fixed depend on viewport

Best-Practive
NavBar, FixedNavBar, ScrollToTop
Cannot use margin for small element like anchor

# Inline Element
- Occupies only space necessary for its content
- no line-break for after and before element
- Cannot apply heights and widths
- paddings and margins are applied only horizontally (Left and Right)

# Inline-Block Element
- Looks inline from the outside, behaves like block-level on the inside
- causes no line-break 
- occupies only content's space
- Block model applies as showed

# Block Element
Block occupies all space that they can and they basically create linebreak
Occupies 100% parent element

+ Default position: Relative

# Absolute Position

# Pseudo Element
syntax with two collon
wanto sibling other element use '+' Symbol

# Flex and CSS Grid Layout

3 Ways building Layout in CSS:
All layout width: 1200px
- Float Layout : Element flowing rounded, remove element out of flow
Text and inline element wrap around floated element
The container will not adjust its height to the element
Clearfix Hack
- Flexbox 
    Flex Container will take the high of the highest element
- CSS Grid

# Box-sizing: border-box
- The box-sizing property allows us to include the padding and border in an element's total width and height.

- If you set box-sizing: border-box; on an element, padding and border are included in the width and height

# Clear property
Thuộc tính clear trong CSS được dùng để ngăn chặn một phần tử "lọt" vào vùng bị ảnh hưởng bởi các phần tử trước đó được float

# Flexbox Layout
- is a set of related CSS properties for building 1-dimensional layouts
- The main idea behind flexbox is that empty space inside a container element can be automatically divided by its child elements
- align items to one another inside a parent container, both horizontally and vertically
- Flexbox solves common problems such as vertical centering and creating equal-height columns

# Flex container
- gap: create space between items without using margin
- justify-content: to align items along main axis (horizontally)
- align-items: to align items along cross axis (vertically)
- flex-direction: to define which is the main axis
- flex-wrap: to allow items to wrap into a new line if they are too large
- align-content: only applies when there are multiple lines

# CSS Grid Layout
- CSS Grid is a set of CSS properties for building 2-dimensional layouts
- The main idea behind CSS Grid is that we divide a container element into rows and
columns that can be filled with its child element
- fr (fraction) can get the highest height of element
- align, justify: end and start

# Aligning items inside cells: moving items

# Position != translate
- Performance
- child element

# Media Query 
- Tinh kha dung tot hon: su pho bien cua thiet bi di dong
- SEO va toi uu hoa cong cu tim kiem

# Bootstrap
- component based
- utility first: Khong co component (Tailwind Css)
- Responsive in bootstrap is always Mobile First
- bootstrap 5 does not depend on Jquery