# Camping-Website

## [Live Website Link!] https://rajakhan017.github.io/Camping-Website/



### In `style.css`

#### `@import`


| CSS Property | Value                 | Explanation                                                                                                                          |
| ------------ | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| margin       | 0                     | Sets the margin of all elements to 0.                                                                                                |
| padding      | 0                     | Sets the padding of all elements to 0.                                                                                               |
| box-sizing   | border-box            | Configures the box model to use `border-box`, where padding and border are included in the element's total width and height.         |
| font-family  | 'Poppins', sans-serif | Sets the font family for all elements to 'Poppins' and falls back to a generic sans-serif font family if 'Poppins' is not available. |

**Selector Explanation**: The `*` selector targets all elements on the page, applying global styles such as resetting margins, padding, setting the box-sizing model, and defining a font family.

#### `body`

| CSS Property | Value   | Explanation                                                                |
| ------------ | ------- | -------------------------------------------------------------------------- |
| background   | #f2f2f2 | Sets the background color of the `body` element to a light gray (#f2f2f2). |

**Selector Explanation**: The `body` selector targets the `body` element, styling it with a light gray background color.

#### `h2:not(.logo)`

| CSS Property | Value | Explanation                                                                       |
| ------------ | ----- | --------------------------------------------------------------------------------- |
| font-size    | 32px  | Sets the font size of `h2` elements with a class other than `.logo` to 32 pixels. |

**Selector Explanation**: The `h2:not(.logo)` selector targets `h2` elements that do not have the class `.logo`, styling them with a specific font size.

#### `section > p`

| CSS Property | Value  | Explanation                                                                                 |
| ------------ | ------ | ------------------------------------------------------------------------------------------- |
| text-align   | center | Centers the text alignment for `p` elements that are direct children of `section` elements. |

**Selector Explanation**: The `section > p` selector targets `p` elements that are direct children of `section` elements, styling them with centered text alignment.

These tables provide a clear breakdown of each CSS selector, their associated properties, and explanations for the values used in the CSS code, including the @import statements for external resources.

### In `header.css`

#### `header`

| CSS Property    | Value   | Explanation                                                                                    |
| --------------- | ------- | ---------------------------------------------------------------------------------------------- |
| position        | fixed   | Sets the position of the `header` element to fixed. It remains fixed relative to the viewport. |
| top             | 0       | Positions the `header` element at the top of the viewport.                                     |
| left            | 0       | Positions the `header` element at the left edge of the viewport.                               |
| z-index         | 9       | Sets the stacking order of the `header` element to 9.                                          |
| width           | 100%    | Sets the width of the `header` element to 100% of the viewport width.                          |
| display         | flex    | Configures the `header` element as a flex container.                                           |
| justify-content | center  | Centers its content horizontally within the `header`.                                          |
| background      | #333333 | Sets the background color of the `header` element to a dark gray (#333333).                    |

**Selector Explanation**: The `header` selector targets the `header` element, styling it with a fixed position at the top of the viewport, dark background color, and flex layout for content alignment.

#### `.navbar`

| CSS Property    | Value         | Explanation                                                                                                           |
| --------------- | ------------- | --------------------------------------------------------------------------------------------------------------------- |
| display         | flex          | Configures elements with the class `.navbar` as flex containers.                                                      |
| padding         | 0 10px        | Sets the padding of elements with the class `.navbar` to 0 on the top and bottom and 10 pixels on the left and right. |
| max-width       | 1200px        | Sets the maximum width of elements with the class `.navbar` to 1200 pixels.                                           |
| width           | 100%          | Sets the width of elements with the class `.navbar` to 100% of their containing element.                              |
| align-items     | center        | Centers content vertically within elements with the class `.navbar`.                                                  |
| justify-content | space-between | Distributes content evenly along the horizontal axis of elements with the class `.navbar`.                            |

**Selector Explanation**: The `.navbar` selector targets elements with the class `.navbar`, styling them as flex containers with specific padding, maximum width, content alignment, and spacing.

#### `.nav-links`

| CSS Property | Value  | Explanation                                                             |
| ------------ | ------ | ----------------------------------------------------------------------- |
| display      | flex   | Configures elements with the class `.nav-links` as flex containers.     |
| align-items  | center | Centers content vertically within elements with the class `.nav-links`. |

**Selector Explanation**: The `.nav-links` selector targets elements with the class `.nav-links`, styling them as flex containers with content alignment.

#### `.nav-links li`

| CSS Property | Value | Explanation                                                                                                    |
| ------------ | ----- | -------------------------------------------------------------------------------------------------------------- |
| list-style   | none  | Removes the default list-style (bullet points) from `li` elements within elements with the class `.nav-links`. |

**Selector Explanation**: The `.nav-links li` selector targets `li` elements within elements with the class `.nav-links`, removing the default list-style.

#### `.logo a`

| CSS Property | Value  | Explanation                                                                         |
| ------------ | ------ | ----------------------------------------------------------------------------------- |
| display      | flex   | Configures `a` elements within elements with the class `.logo` as flex containers.  |
| align-items  | center | Centers content vertically within `a` elements with the class `.logo`.              |
| margin-left  | 0      | Resets the left margin of `a` elements within elements with the class `.logo` to 0. |

**Selector Explanation**: The `.logo a` selector targets `a` elements within elements with the class `.logo`, styling them as flex containers with centered content alignment and resetting the left margin.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/b40dfe6a-95b9-4cbb-925e-083039d091f2)

#### `header a`

| CSS Property    | Value  | Explanation                                                                                                         |
| --------------- | ------ | ------------------------------------------------------------------------------------------------------------------- |
| margin-left     | 40px   | Adds left margin of 40 pixels to `a` elements within `header`.                                                      |
| text-decoration | none   | Removes the default text decoration (underline) from `a` elements within `header`.                                  |
| color           | #fff   | Sets the text color of `a` elements within `header` to white (#fff).                                                |
| height          | 100%   | Sets the height of `a` elements within `header` to 100% of their containing element.                                |
| padding         | 20px 0 | Adds padding of 20 pixels on the top and bottom and 0 pixels on the left and right to `a` elements within `header`. |

**Selector Explanation**: The `header a` selector targets `a` elements within `header`, styling them with specific margins, text decoration, color, height, and padding.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/22cf3775-d988-4dee-88ad-fe8d5e7e2187)

#### `header a:hover`

| CSS Property | Value | Explanation                                                                        |
| ------------ | ----- | ---------------------------------------------------------------------------------- |
| color        | #ddd  | Sets the text color of `a` elements within `header` to light gray (#ddd) on hover. |

**Selector Explanation**: The `header a:hover` selector targets `a` elements within `header` when they are hovered over, changing the text color to light gray.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/52f4bb4a-d775-4055-9b3f-e426b437f4d8)

### In `landing.css`

#### `.landing`

| CSS Property          | Value                                                                                   | Explanation                                                                                   |
| --------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| height                | 100vh                                                                                   | Sets the height of elements with the class `.landing` to 100% of the viewport height.         |
| width                 | 100%                                                                                    | Sets the width of elements with the class `.landing` to 100% of their containing element.     |
| position              | relative                                                                                | Sets the positioning context for elements with the class `.landing` to relative.              |
| background            | url('https://koa.com/blog/images/family-camping-at-sunset.jpg?preset=heroimagecropped') | Sets the background image of elements with the class `.landing` to a specified image URL.     |
| background-position   | center 65%                                                                              | Positions the background image horizontally at the center and vertically at 65% from the top. |
| background-size       | cover                                                                                   | Scales the background image to cover the entire element.                                      |
| background-attachment | fixed                                                                                   | Fixes the background image in place so it doesn't scroll with the content.                    |

**Selector Explanation**: The `.landing` selector targets elements with the class `.landing`, styling them with a full-height background image, positioned and scaled to cover the element, with a fixed attachment.

#### `.landing::after`

| CSS Property | Value              | Explanation                                                                               |
| ------------ | ------------------ | ----------------------------------------------------------------------------------------- |
| content      | ''                 | Sets empty content for pseudo-elements created by `.landing::after`.                      |
| position     | absolute           | Positions the pseudo-element absolutely within its containing element.                    |
| left         | 0                  | Positions the left edge of the pseudo-element at the left edge of its containing element. |
| top          | 0                  | Positions the top edge of the pseudo-element at the top edge of its containing element.   |
| height       | 100%               | Sets the height of the pseudo-element to 100% of its containing element.                  |
| width        | 100%               | Sets the width of the pseudo-element to 100% of its containing element.                   |
| background   | rgba(0, 0, 0, 0.2) | Sets the background color of the pseudo-element to a semi-transparent black.              |

**Selector Explanation**: The `.landing::after` selector creates a pseudo-element that covers the entire `.landing` element with a semi-transparent black overlay.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/42c16ac4-41a0-43f3-879c-b7383fd3af91)

#### `.container`

| CSS Property    | Value  | Explanation                                                                                 |
| --------------- | ------ | ------------------------------------------------------------------------------------------- |
| display         | flex   | Configures elements with the class `.container` as flex containers.                         |
| height          | 85%    | Sets the height of elements with the class `.container` to 85% of their containing element. |
| z-index         | 1      | Sets the stacking order of elements with the class `.container` to 1.                       |
| align-items     | center | Centers content vertically within elements with the class `.container`.                     |
| justify-content | center | Centers content horizontally within elements with the class `.container`.                   |
| flex-direction  | column | Sets the flex direction of elements with the class `.container` to column.                  |

**Selector Explanation**: The `.container` selector targets elements with the class `.container`, styling them as flex containers with centered content alignment both vertically and horizontally.

#### `h1`

| CSS Property  | Value | Explanation                                                |
| ------------- | ----- | ---------------------------------------------------------- |
| font-size     | 60px  | Sets the font size of `h1` elements to 60 pixels.          |
| font-weight   | 700   | Sets the font weight of `h1` elements to 700 (bold).       |
| margin-bottom | 10px  | Adds a margin of 10 pixels to the bottom of `h1` elements. |

**Selector Explanation**: The `h1` selector targets `h1` elements, styling them with a specific font size, bold text, and a margin at the bottom.

#### `.desc`

| CSS Property  | Value                           | Explanation                                                                     |
| ------------- | ------------------------------- | ------------------------------------------------------------------------------- |
| margin-bottom | 50px                            | Adds a margin of 50 pixels to the bottom of elements with the class `.desc`.    |
| color         | #fff                            | Sets the text color of elements with the class `.desc` to white (#fff).         |
| font-size     | 20px                            | Sets the font size of elements with the class `.desc` to 20 pixels.             |
| text-align    | center                          | Centers the text horizontally within elements with the class `.desc`.           |
| text-shadow   | 0px 0px 10px rgba(0, 0, 0, 0.3) | Adds a text shadow with specific parameters to elements with the class `.desc`. |

**Selector Explanation**: The `.desc` selector targets elements with the class `.desc`, styling them with specific margins, text color, font size, centered text alignment, and a text shadow.

#### `.container a`

| CSS Property   | Value     | Explanation                                                                                                              |
| -------------- | --------- | ------------------------------------------------------------------------------------------------------------------------ |
| color          | #000      | Sets the text color of `a` elements within elements with the class `.container` to black (#000).                         |
| display        | block     | Configures `a` elements within elements with the class `.container` as block-level elements.                             |
| text-transform | uppercase | Transforms the text within `a` elements to uppercase.                                                                    |
| font-size      | 18px      | Sets the font size of `a` elements within elements with the class `.container` to 18 pixels.                             |
| margin         | 0 10px    | Sets margins of 0 pixels on the top and bottom and 10 pixels on the left and right for `a` elements within `.container`. |
| padding        | 10px 30px | Adds padding of 10 pixels on the top and bottom and 30 pixels on the left and right to `a` elements within `.container`. |
| border-radius  | 5px       | Sets the border radius of `a` elements within `.container` to 5 pixels.                                                  |
| background     | #fff      |

                                                                                                   | Sets the background color of `a` elements within `.container` to white (#fff).                       |

| border | 2px solid #fff | Sets a 2-pixel solid white border for `a` elements within `.container`. |
| transition | 0.4s ease | Adds a transition effect with a duration of 0.4 seconds and easing function to `a` elements within `.container`. |
| box-shadow | 0 10px 20px rgba(0, 0, 0, 0.3) | Adds a box shadow with specific parameters to `a` elements within `.container`. |
| text-decoration | none | Removes the default underline text decoration for `a` elements within `.container`. |

**Selector Explanation**: The `.container a` selector targets `a` elements within elements with the class `.container`, styling them with specific text properties, padding, border, background, and transition effects.

#### `section`

| CSS Property   | Value    | Explanation                                                                              |
| -------------- | -------- | ---------------------------------------------------------------------------------------- |
| display        | flex     | Configures `section` elements as flex containers.                                        |
| align-items    | center   | Centers content vertically within `section` elements.                                    |
| flex-direction | column   | Sets the flex direction of `section` elements to column.                                 |
| padding        | 80px 0 0 | Adds padding to the top of `section` elements and sets padding to 0 for the other sides. |

**Selector Explanation**: The `section` selector targets `section` elements, styling them as flex containers with centered content alignment vertically and a padding of 80 pixels at the top.

### In `cards.css`

#### `.cards`

| CSS Property    | Value         | Explanation                                                                                                             |
| --------------- | ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| display         | flex          | Configures elements with the class `.cards` as flex containers.                                                         |
| flex-wrap       | wrap          | Allows elements with the class `.cards` to wrap to the next line if they exceed the container's width.                  |
| max-width       | 1200px        | Sets the maximum width of elements with the class `.cards` to 1200 pixels.                                              |
| margin-top      | 50px          | Adds a margin of 50 pixels to the top of elements with the class `.cards`.                                              |
| padding         | 0 10px        | Adds padding of 0 pixels on the top and bottom and 10 pixels on the left and right to elements with the class `.cards`. |
| justify-content | space-between | Distributes space between elements with the class `.cards`, pushing them as far apart as possible.                      |

**Selector Explanation**: The `.cards` selector targets elements with the class `.cards`, styling them as a flex container with specific layout properties to create a card-like grid.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/f3f0bb8f-5336-41a1-bdb4-a348673cfda0)

#### `.card`

| CSS Property  | Value                            | Explanation                                                                                                                                |
| ------------- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| background    | #fff                             | Sets the background color of elements with the class `.card` to white (#fff).                                                              |
| padding       | 40px 15px                        | Adds padding of 40 pixels on the top and bottom and 15 pixels on the left and right to elements with the class `.card`.                    |
| list-style    | none                             | Removes the default list-style (bullets) for elements with the class `.card`.                                                              |
| border-radius | 5px                              | Rounds the corners of elements with the class `.card`, giving them a border radius of 5 pixels.                                            |
| box-shadow    | 0px 5px 10px rgba(0, 0, 0, 0.04) | Adds a box shadow to elements with the class `.card` with specific parameters for a subtle shadow effect.                                  |
| margin-bottom | 40px                             | Adds a margin of 40 pixels to the bottom of elements with the class `.card`.                                                               |
| width         | calc(100% / 3 - 30px)            | Sets the width of elements with the class `.card` to one-third of the container width minus 30 pixels, allowing for spacing between cards. |
| text-align    | center                           | Centers text horizontally within elements with the class `.card`.                                                                          |

**Selector Explanation**: The `.card` selector targets elements with the class `.card`, styling them as individual cards with specific background color, padding, border radius, and box shadow. The cards are also centered horizontally, and their width is calculated to create a grid of three cards per row.

#### `.card img`

| CSS Property  | Value | Explanation                                                                                                                            |
| ------------- | ----- | -------------------------------------------------------------------------------------------------------------------------------------- |
| width         | 120px | Sets the width of `img` elements within elements with the class `.card` to 120 pixels.                                                 |
| height        | 120px | Sets the height of `img` elements within elements with the class `.card` to 120 pixels.                                                |
| margin-bottom | 20px  | Adds a margin of 20 pixels to the bottom of `img` elements within elements with the class `.card`.                                     |
| border-radius | 100%  | Rounds the corners of `img` elements within elements with the class `.card`, creating circular images.                                 |
| object-fit    | cover | Scales `img` elements within elements with the class `.card` to cover the entire available space while maintaining their aspect ratio. |

**Selector Explanation**: The `.card img` selector targets `img` elements within elements with the class `.card`, styling them with a specific width, height, margin, border radius, and object-fit property.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/eacdfe19-67ad-4ef1-9ca8-5042d280a9f4)

#### `.card p`

| CSS Property | Value  | Explanation                                                                                                                                |
| ------------ | ------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| padding      | 0 15px | Adds padding of 0 pixels on the top and bottom and 15 pixels on the left and right to `p` elements within elements with the class `.card`. |
| margin-top   | 5px    | Adds a margin of 5 pixels to the top of `p` elements within elements with the class `.card`.                                               |

**Selector Explanation**: The `.card p` selector targets `p` elements within elements with the class `.card`, styling them with specific padding and margin properties.

### In `about.css`

#### .about

| Property    | Value    | Description                           |
| ----------- | -------- | ------------------------------------- |
| `margin`    | `0 auto` | Center the element horizontally.      |
| `max-width` | `1200px` | Set the maximum width of the element. |

**Selector Explanation:** The `.about` selector targets elements with the class "about."
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/d6610503-8329-4262-b9e7-cd79f10f3c6b)


#### .company-info

| Property     | Value  | Description                           |
| ------------ | ------ | ------------------------------------- |
| `margin-top` | `30px` | Add margin to the top of the element. |

**Selector Explanation:** The `.company-info` selector targets elements with the class "company-info."

#### .about h3

| Property | Value         | Description                                                        |
| -------- | ------------- | ------------------------------------------------------------------ |
| `margin` | `30px 0 10px` | Set margins for top, right, bottom, and left sides of the element. |

**Selector Explanation:** The `.about h3` selector targets `h3` elements that are descendants of elements with the class "about."

#### .team

| Property     | Value  | Description                                            |
| ------------ | ------ | ------------------------------------------------------ |
| `text-align` | `left` | Align text content to the left.                        |
| `width`      | `100%` | Set the element's width to 100% of its parent's width. |

**Selector Explanation:** The `.team` selector targets elements with the class "team."

#### .team ul

| Property       | Value  | Description                                       |
| -------------- | ------ | ------------------------------------------------- |
| `padding-left` | `20px` | Add padding to the left side of the `ul` element. |

**Selector Explanation:** The `.team ul` selector targets `ul` elements that are descendants of elements with the class "team."

#### .info, .mission, .team

| Property  | Value    | Description                                                                                                                 |
| --------- | -------- | --------------------------------------------------------------------------------------------------------------------------- |
| `padding` | `0 10px` | Set padding for top and bottom (0) and left and right (10px) sides of elements with class `.info`, `.mission`, and `.team`. |

**Selector Explanation:** The `.info`, `.mission`, `.team` selectors target elements with the classes "info," "mission," and "team" respectively.

### In `contact.css`

#### .contact-box

| Property          | Value           | Description                                                                    |
| ----------------- | --------------- | ------------------------------------------------------------------------------ |
| `margin`          | `60px 0 90px`   | Set margins for top (60px), right (0), and bottom (90px) sides of the element. |
| `display`         | `flex`          | Set the element to use flexbox layout.                                         |
| `max-width`       | `1200px`        | Set the maximum width of the element.                                          |
| `width`           | `100%`          | Set the element's width to 100% of its parent's width.                         |
| `align-items`     | `center`        | Align flex items vertically at the center.                                     |
| `justify-content` | `space-between` | Distribute space evenly between flex items.                                    |

**Selector Explanation:** The `.contact-box` selector targets elements with the class "contact-box."

#### .box

| Property  | Value                   | Description                                                                        |
| --------- | ----------------------- | ---------------------------------------------------------------------------------- |
| `padding` | `0 10px`                | Set padding for top and bottom (0) and left and right (10px) sides of the element. |
| `width`   | `calc(100% / 2 - 50px)` | Calculate the element's width dynamically based on the parent's width.             |
| `p`       | `margin-bottom: 10px;`  | Add margin to the bottom of `p` elements inside this element.                      |

**Selector Explanation:** The `.box` selector targets elements with the class "box."

#### p svg

| Property       | Value     | Description                                                               |
| -------------- | --------- | ------------------------------------------------------------------------- |
| `fill`         | `#7a7a7a` | Set the fill color of SVG elements within `p` elements to #7a7a7a (gray). |
| `margin-right` | `10px`    | Add margin to the right side of SVG elements within `p` elements.         |

**Selector Explanation:** The `p svg` selector targets SVG elements that are descendants of `p` elements.

#### form input

| Property        | Value               | Description                                                 |
| --------------- | ------------------- | ----------------------------------------------------------- |
| `height`        | `45px`              | Set the height of input elements to 45px.                   |
| `margin-bottom` | `20px`              | Add margin to the bottom of input elements.                 |
| `padding`       | `10px`              | Add padding to input elements.                              |
| `width`         | `100%`              | Set the width of input elements to 100% of their container. |
| `font-size`     | `16px`              | Set the font size of input elements to 16px.                |
| `outline`       | `none`              | Remove the outline border on input elements.                |
| `border`        | `1px solid #bfbfbf` | Set a 1px solid border on input elements.                   |

**Selector Explanation:** The `form input` selector targets input elements within `form` elements.

#### form textarea

| Property    | Value               | Description                                                    |
| ----------- | ------------------- | -------------------------------------------------------------- |
| `padding`   | `10px`              | Add padding to textarea elements.                              |
| `width`     | `100%`              | Set the width of textarea elements to 100% of their container. |
| `font-size` | `16px`              | Set the font size of textarea elements to 16px.                |
| `height`    | `150px`             | Set the height of textarea elements to 150px.                  |
| `outline`   | `none`              | Remove the outline border on textarea elements.                |
| `resize`    | `vertical`          | Allow vertical resizing of textarea elements.                  |
| `border`    | `1px solid #bfbfbf` | Set a 1px solid border on textarea elements.                   |

**Selector Explanation:** The `form textarea` selector targets textarea elements within `form` elements.

#### form button

| Property        | Value       | Description                                                                                   |
| --------------- | ----------- | --------------------------------------------------------------------------------------------- |
| `margin-top`    | `10px`      | Add margin to the top of button elements.                                                     |
| `padding`       | `10px 20px` | Set padding for the top and bottom (10px) and left and right (20px) sides of button elements. |
| `font-size`     | `17px`      | Set the font size of button elements to 17px.                                                 |
| `color`         | `#fff`      | Set the text color of button elements to white.                                               |
| `border`        | `none`      | Remove the border on button elements.                                                         |
| `cursor`        | `pointer`   | Set the cursor to a pointer (hand) on button elements.                                        |
| `border-radius` | `5px`       | Add rounded corners (5px) to button elements.                                                 |
| `background`    | `#333`      | Set the background color of button elements to #333 (dark gray).                              |
| `transition`    | `0.2s ease` | Add a smooth transition effect with a duration of 0.2 seconds.                                |

**Selector Explanation:** The `form button` selector targets button elements within `form` elements.
![image](https://github.com/rajakhan017/Camping-Website/assets/135150598/f0c975f8-2958-470f-9e42-fdefe019cc07)


#### form button:hover

| Property     | Value     | Description                                                                       |
| ------------ | --------- | --------------------------------------------------------------------------------- |
| `background` | `#525252` | Change the background color of button elements to #525252 (darker gray) on hover. |

**Selector Explanation:** The `form button:hover` selector targets button elements within `form` elements when they are hovered over.
