# Hosted Link : https://mansi2020.github.io/css_weeklyTest_4/
<h1> UI : navbar</h1>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/6e6d52c0-a96a-4af9-9bd3-0b7afeb651d4">
<h2>HTML code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/b1efa8cf-fccb-4637-97d6-d3e01806f480">
nav: The nav tag represents a section of a web page that contains navigation links. It is used to define a set of navigation links that can direct users to different parts of the website or to external websites.  

h2: The h2 tag is a heading element in HTML, and it represents a second-level heading.  

header: The header tag is used to define the header section of a web page. It usually contains introductory content, headings, logos, navigation menus, and other elements that are meant to appear at the top of the page.  

ul: The ul tag stands for "unordered list." It is used to create a list of items where the order of the items is not important. Each list item is defined using the li tag, which is placed within the ul tag.

a: a tag is used to create hyperlinks in HTML. It allows you to link to other web pages, files, or resources on the internet.   

<h2>CSS code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/050d5388-be2e-4b97-8a11-01143f080e98">
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/d7ac49c2-d5f2-4016-a391-4e2be1c859cf">  

scroll-behavior: smooth => This property sets the scrolling behavior for anchor links within a page. When applied, clicking on an anchor link will result in a smooth scrolling animation to the target destination on the page.

background: This property is used to set the background style of an element, which can include color, images, gradients, and other background-related properties. 

width: 100%: This property sets the width of an element to 100% of its containing element's width. This makes the element span the entire width of its parent container.

display: flex: This property specifies the display behavior of an element as a flex container. Flex containers allow their child elements to be laid out in a flexible and responsive manner using flex layout properties.


justify-content: center: This property aligns the flex items (child elements of a flex container) along the main axis and distributes extra space around them, so they are centered horizontally in this case.


position: fixed;: This property positions an element relative to the viewport, creating a fixed position. The element remains in a fixed position even when the user scrolls, making it appear as if it's "stuck" in place.


top: 0; and left: 0;: These properties, when used with position: fixed;, position the element at the top-left corner of the viewport.


align-items: center: This property aligns the flex items vertically along the cross axis (perpendicular to the main axis), so they are centered vertically in this case.


z-index: This property sets the stacking order of an element on the z-axis (depth) relative to other elements. Elements with higher z-index values appear above those with lower values.

width: 1200px: This property sets the width of the element to a fixed value of 1200 pixels.  

padding: 0 10px: This property defines the padding space inside the element. It has no padding at the top and bottom and 10 pixels of padding on the left and right.

max-width: 100%: This property sets the maximum width of the element to be 100% of its containing element's width, ensuring it doesn't exceed the viewport width.

font-size: This property sets the font size of the text inside the element .

font-weight: bold: This property sets the weight (thickness) of the text characters to bold.

text-decoration: none: This property removes the default underlining of text links (anchors).

color: white: This property sets the color of the text content to white.

display: inline-block: This property changes the display behavior of the element to inline-block. The element behaves like an inline element but retains the ability to have width, height, margins, and padding like a block element.
<hr>
<h1> UI : home page section</h1>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/dd318bb8-6ee1-4bd8-8a87-24b6fdd6f42d">
<h2>HTML code</h2>  
div: The div tag is a generic container element in HTML that is used to group and style other HTML elements together.   

section: The section tag represents a thematic grouping of content on a web page. It is used to mark up distinct sections or blocks of content that are thematically related.  

a: a tag is used to create hyperlinks in HTML. It allows you to link to other web pages, files, or resources on the internet.   

p: The p tag stands for paragraph.  

<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/6401ef01-e91f-46fc-a108-05ba12b30437">
<h2>CSS code</h2>  
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/3895000d-505d-4b07-99ac-c3e7da4494d9">
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/09f1ccbd-f8b0-4a1d-be0e-24348f96f671">
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/4e098147-f263-4479-9309-fdc312b0cbaa">

position: relative: This property positions the element relative to its normal position in the document flow. It serves as a basis for absolutely positioned child elements.

background-size: cover;: This property specifies how the background image should be sized in relation to its container. The cover value ensures that the background image covers the entire container, while maintaining its aspect ratio.

background-attachment: fixed;: This property sets whether the background image should scroll with the rest of the content or remain fixed as the user scrolls. With fixed, the background image stays fixed in the viewport.

background-position: center 65%;: This property sets the initial position of the background image. center horizontally centers the image, while 65% vertically positions it 65% from the top of the container.
 
::before : This is a pseudo-element that allows you to insert content before the content of an element. It's often used for decorative or stylistic purposes.

content: "": This property sets the content that will be displayed before the ::before pseudo-element. In this case, it's set to an empty string, so no visible content is added.

position: absolute;: This property positions the pseudo-element absolutely within its containing element, allowing it to be placed anywhere within that container.

text-shadow: This property adds a shadow to the text content of the pseudo-element. The values specify the horizontal and vertical offsets, blur radius, and color of the shadow.

display: flex;: This property sets the display behavior of the pseudo-element to a flex container, allowing its children to be laid out using flex layout properties.

flex-direction: column: This property specifies the direction in which flex items (children of the pseudo-element) are laid out. column arranges them vertically.

padding: The value is missing here. Padding adds space within the element. You should provide values like padding: 10px;.

align-items: center: This property aligns the flex items vertically (along the cross axis) at the center.

z-index: The value is missing. The z-index property sets the stacking order of elements. Higher values stack above lower values.

text-transform: uppercase: This property transforms the text to uppercase. 

border-radius: The value is missing here. This property defines the curvature of the element's corners. For example, border-radius: 5px;.

transition: 0.4s ease: This property specifies the transition effect applied to changes in the element's properties over a duration of 0.4 seconds, using an ease timing function.

border: The value is missing here. The border property sets the style, width, and color of the element's border.

box-shadow: The value is missing here. This property adds a shadow to the entire element, providing a visual depth effect.
<hr>
<h1> UI : our services section</h1>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/3653349e-b48d-44a0-ad3f-846c13b5d1dc">
<h2>HTML code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/6c39e66a-9b08-40aa-bf1f-b0b2ec9c298c">
img : The img tag in HTML is used to embed images on a web page.  

div: The div tag is a generic container element in HTML that is used to group and style other HTML elements together.   

section: The section tag represents a thematic grouping of content on a web page. It is used to mark up distinct sections or blocks of content that are thematically related.  

a: a tag is used to create hyperlinks in HTML. It allows you to link to other web pages, files, or resources on the internet.   

p: The p tag stands for paragraph. 
<h2>CSS code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/e92fda82-1f86-48ce-8d64-5bdb831732cf)">
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/cd7cab6f-b2cf-4d1e-89a3-245aa377f3ca)">  

display: flex;: This property sets the display behavior of the element as a flex container. Flex containers enable their child elements to be laid out in a flexible and responsive manner using flex layout properties.  

flex-wrap: wrap => This property specifies whether flex items  should wrap to multiple lines if they exceed the container's width. wrap value allows items to wrap onto additional lines as needed.


max-width: 1200px; : This property sets the maximum width of the element to 1200 pixels. The element will not exceed this width even if the container allows more space.

justify-content: space-between;: This property aligns flex items along the main axis with space distributed evenly between the items. The space-between value pushes the first and last items to the edges of the container with equal space between the remaining items.


background-color: ...; : This property sets the background color of the element. You should provide a valid color value (e.g., hex code, RGB, color name) to fill the background with a specific color.


object-fit: cover;: This property specifies how an image or video should be resized to fit within a container while maintaining its aspect ratio. The cover value scales the image proportionally to cover the entire container, potentially cropping parts of the image.


line-height: ...;: This property sets the spacing between lines of text within an element. You should provide a unit value (e.g., pixels, ems) to determine the amount of spacing.


font-size: ...;: This property sets the size of the font used for text within the element. You should provide a unit value (e.g., pixels, ems) to determine the font size.


letter-spacing: ...;: This property adjusts the spacing between individual characters in text. You should provide a unit value (e.g., pixels, ems) to control the letter spacing.
<hr>
<h1> UI : About Us section</h1>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/91a0a892-0ab3-422b-8c58-bfa9b702abbb">
<h2>HTML code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/ae262a42-474b-4a5d-86d1-1f22159433cf">
div: The div tag is a generic container element in HTML that is used to group and style other HTML elements together.   

section: The section tag represents a thematic grouping of content on a web page. It is used to mark up distinct sections or blocks of content that are thematically related.  

a: a tag is used to create hyperlinks in HTML. It allows you to link to other web pages, files, or resources on the internet.   

p: The p tag stands for paragraph.  

ul: The ul tag stands for "unordered list." It is used to create a list of items where the order of the items is not important. Each list item is defined using the li tag, which is placed within the ul tag.  

<h2>CSS code</h2>  
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/d24d889c-4095-454e-b18c-a91e36bc49f8">
max-width: 1200px;: This property sets the maximum width of the element to 1200 pixels. The element will not exceed this width, helping to control its layout on wider screens.

margin: 0 auto;: This property defines the margins of the element. Setting 0 for the top and bottom margins and auto for the left and right margins horizontally centers the element within its containing element.

font-weight: This property adjusts the thickness of the characters in the text. You should provide a numeric value (e.g., bold, normal, 700, 900) to set the desired font weight.

padding: This property sets the spacing within the element, between the content and the element's border. You should provide a value (e.g., pixels, ems) to control the padding on all sides or individually (e.g., padding: 10px; or padding: 10px 20px;).

line-height: 25px;: This property sets the vertical spacing between lines of text within the element. You should provide a unit value (e.g., pixels, ems) to determine the amount of spacing.  

font-size: This property sets the size of the font used for text within the element. You should provide a unit value (e.g., pixels, ems) to determine the font size.
<hr>
<h1> UI : Contact Us section</h1>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/57cec87b-94da-49f4-8a03-3afb16cf7637">
<h2>HTML code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/f9c4cb2e-3b45-446f-8721-c629ccf21306"> 
div: The div tag is a generic container element in HTML that is used to group and style other HTML elements together.   

section: The section tag represents a thematic grouping of content on a web page. It is used to mark up distinct sections or blocks of content that are thematically related.  

a: a tag is used to create hyperlinks in HTML. It allows you to link to other web pages, files, or resources on the internet.   

p: The p tag stands for paragraph.    

textarea: The textarea tag is used to create a multi-line text input area on a web page. It allows users to enter longer paragraphs or blocks of text.   

form: The form tag is used to create an HTML form that collects and submits user input.    

input: The input tag is used to create various types of input fields within a form. It allows users to provide different types of input, such as text, email, password, radio buttons, checkboxes, and more.  

button: The button tag creates a clickable button element on a web page.  

<h2>CSS code</h2>
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/e2797d80-5a6f-4e3a-a531-d10eca70ce35">
<img src="https://github.com/mansi2020/css_weeklyTest_4/assets/57188328/9525413e-9f17-4bc7-a72e-757b7fe137db">
font-weight: This property adjusts the thickness of the characters in the text. You should provide a numeric value (e.g., bold, normal, 700, 900) to set the desired font weight.

display: flex;: This property sets the display behavior of the element as a flex container. Flex containers enable their child elements to be laid out in a flexible and responsive manner using flex layout properties.

align-items: center;: This property aligns flex items vertically (along the cross axis) within the flex container, ensuring they are centered vertically.

justify-content: space-between;: This property aligns flex items horizontally along the main axis with space distributed evenly between the items. The space-between value pushes the first and last items to the edges of the container with equal space between the remaining items.

border: none;: This property removes the border around the element. The value none ensures that there is no visible border.

border-radius:: This property sets the curvature of the element's corners. You should provide a unit value (e.g., pixels, ems) to control the border radius and create rounded corners.

background-color:: This property sets the background color of the element. You should provide a valid color value (e.g., hex code, RGB, color name) to fill the background with a specific color.

transition: 0.3s ease;: This property specifies the transition effect applied to changes in the element's properties over a duration of 0.3 seconds, using an ease timing function.  

:hover Pseudo-class: The :hover pseudo-class is used to target an element when a user hovers their mouse pointer over it. You can apply additional styles to the element when it's being hovered over.
