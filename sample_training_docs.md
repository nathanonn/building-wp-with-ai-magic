# About Us with Large Image

## PURPOSE:

The purpose of this layout is to introduce technology to society. It aims to engage the reader with an eye-catching image and informative text about how technology is being introduced and incorporated into people's lives.

## DESCRIPTION:

The layout consists of two main sections:

1. A full-width header with a background image showing hands typing on a laptop keyboard. This sets the technology theme.

2. A two-column section below the header. The left narrower column has the section title "About Us" and main heading "Introducing Technology to Society". The right wider column contains two paragraphs of placeholder text describing the topic in more detail, followed by a "Read More" button.

The color scheme uses dark text on a white background, with an accent color used for the section title and button. The fonts are a bold sans-serif for the headings and a regular sans-serif for the body text.

## INSTRUCTIONS:

1. Insert a Columns block and set it to wide width, vertically centered, white background. Configure margin and padding.

2. In the column, insert a Cover block. Set a tech-related background image, set a height of 460px.

3. Below the Columns block, insert another Columns block, also wide width. Set top margin, bottom padding, left/right padding, white background. Configure it to have 2 uneven columns (40%/60%).

4. In the left column, insert a Heading block for the section title. Style it with accent color, uppercase, small size, letter spacing.

5. Below that, insert a Heading block for the main title. Make it large sized, normal weight.

6. In the right column, add two Paragraph blocks with the placeholder text. Style with a gray text color and line height.

7. Below the paragraphs, insert a Buttons block. Configure it with a single left-aligned button. Style the button with rounded corners, white text, and a vivid gradient background.

## Block Pattern

```
<!-- wp:columns {"verticalAlignment":"center","align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"blockGap":{"top":"0","left":"0px"},"padding":{"top":"0px","bottom":"0px","left":"0","right":"0"}}},"backgroundColor":"white"} -->
<div class="wp-block-columns alignwide are-vertically-aligned-center has-white-background-color has-background" style="margin-bottom:0;padding-top:0px;padding-right:0;padding-bottom:0px;padding-left:0"><!-- wp:column {"verticalAlignment":"center","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}},"border":{"width":"0px","style":"none"}}} -->
<div class="wp-block-column is-vertically-aligned-center has-text-color has-link-color" style="border-style:none;border-width:0px;color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:cover {"url":"https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L25zNDIzNy1pbWFnZS1rd3Z5YjZ3eC5qcGc.jpg","dimRatio":0,"minHeight":460,"isDark":false,"layout":{"type":"constrained"}} -->
<div class="wp-block-cover is-light" style="min-height:460px"><span aria-hidden="true" class="wp-block-cover__background has-background-dim-0 has-background-dim"></span><img class="wp-block-cover__image-background" alt="" src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L25zNDIzNy1pbWFnZS1rd3Z5YjZ3eC5qcGc.jpg" data-object-fit="cover" /><div class="wp-block-cover__inner-container"><!-- wp:paragraph {"align":"center","placeholder":"Write title…","fontSize":"large"} -->
<p class="has-text-align-center has-large-font-size"> </p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:cover --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:columns {"verticalAlignment":"top","align":"wide","style":{"spacing":{"margin":{"top":"25px","bottom":"0"},"blockGap":{"left":"20px"},"padding":{"top":"0px","bottom":"60px","left":"var:preset|spacing|50","right":"var:preset|spacing|50"}}},"backgroundColor":"white"} -->
<div class="wp-block-columns alignwide are-vertically-aligned-top has-white-background-color has-background" style="margin-top:25px;margin-bottom:0;padding-top:0px;padding-right:var(--wp--preset--spacing--50);padding-bottom:60px;padding-left:var(--wp--preset--spacing--50)"><!-- wp:column {"verticalAlignment":"top","width":"40%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"32px","right":"0em","bottom":"0em","left":"0em"},"blockGap":"9px"},"border":{"width":"0px","style":"none"}}} -->
<div class="wp-block-column is-vertically-aligned-top has-text-color has-link-color" style="border-style:none;border-width:0px;color:#000000;padding-top:32px;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:40%"><!-- wp:heading {"level":4,"style":{"typography":{"fontSize":"13px","textTransform":"uppercase","letterSpacing":"3px","lineHeight":"1","fontStyle":"normal","fontWeight":"600"},"elements":{"link":{"color":{"text":"#7d9bf6"}}},"color":{"text":"#7d9bf6"}}} -->
<h4 class="wp-block-heading has-text-color has-link-color" style="color:#7d9bf6;font-size:13px;font-style:normal;font-weight:600;letter-spacing:3px;line-height:1;text-transform:uppercase">About Us</h4>
<!-- /wp:heading -->

<!-- wp:heading {"textAlign":"left","style":{"typography":{"fontSize":"48px","fontStyle":"normal","fontWeight":"600"}}} -->
<h2 class="wp-block-heading has-text-align-left" style="font-size:48px;font-style:normal;font-weight:600">Introducing  Technology  to Society</h2>
<!-- /wp:heading --></div>
<!-- /wp:column -->

<!-- wp:column {"verticalAlignment":"top","width":"60%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","bottom":"0em","left":"32px"},"blockGap":"10px"},"border":{"width":"0px","style":"none"}}} -->
<div class="wp-block-column is-vertically-aligned-top has-text-color has-link-color" style="border-style:none;border-width:0px;color:#000000;padding-top:0em;padding-bottom:0em;padding-left:32px;flex-basis:60%"><!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#8b8b8b"}}},"color":{"text":"#8b8b8b"},"typography":{"lineHeight":"1.5"},"spacing":{"margin":{"top":"25px"}}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#8b8b8b;margin-top:25px;line-height:1.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#8b8b8b"}}},"color":{"text":"#8b8b8b"},"typography":{"lineHeight":"1.5"},"spacing":{"margin":{"top":"25px"}}}} -->
<p class="has-text-color has-link-color" style="color:#8b8b8b;margin-top:25px;line-height:1.5">The passage experienced a surge in popularity during the 1960s when Letraset used it on their dry-transfer sheets, and again during the 90s as desktop publishers bundled the text with their software. Today it's seen all around the web; on templates, websites, and stock designs. Use our generator to get your own, or read on for the authoritative history of lorem ipsum.</p>
<!-- /wp:paragraph -->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"left"},"style":{"spacing":{"margin":{"top":"32px"}}}} -->
<div class="wp-block-buttons" style="margin-top:32px"><!-- wp:button {"textAlign":"center","textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"border":{"radius":"5px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"10px","bottom":"10px"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color has-text-align-center wp-element-button" style="border-radius:5px;padding-top:10px;padding-bottom:10px">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# About Us

## PURPOSE:

The purpose of the two-column layout is to effectively communicate the company's story and value proposition. The layout aims to engage visitors by combining a visually appealing image with concise and compelling text content, encouraging them to learn more about the company's mission of integrating AI into education to create a positive impact on society.

## DESCRIPTION:

The image showcases a two-column layout with a white background. The left column features an indoor office setting image with rounded corners on the top-left and bottom-right. The right column contains a small blue heading, a larger black heading, a paragraph of text, a blue "Learn More" button, and a phone number. The content discusses integrating AI into education and the benefits of full site editing in WordPress.

## INSTRUCTIONS:

1. Create a two-column block:

   - Add a "Columns" block with center vertical alignment and wide width.
   - Set the white background color.
   - Adjust margin, padding, and block gap settings as specified in the code.

2. Left column - Add an image:

   - Insert a "Cover" block inside the left column.
   - Set the image URL to the specified URL in the code.
   - Set the dim ratio to 0% and minimum height to 500px.
   - Choose a light text color.
   - Apply a 100px border radius to the top-left and bottom-right corners.

3. Right column - Add text content:
   a. Small heading:
   - Add a "Heading" block for the "OUR STORY" text.
   - Set the color, font size (14px), weight (600), text transform (uppercase), and letter spacing (2px) as specified.
     b. Large heading:
   - Add another "Heading" block for the title text.
   - Set the font size (40px), weight (600), and line height (1.2).
     c. Paragraph:
   - Add a "Paragraph" block for the body text.
   - Apply the specified text color, font style (normal), font weight (300), line height (1.5), and top margin (30px).
     d. Button and phone number:
   - Add a "Group" block with flex layout.
   - Inside the group, add a "Button" block with blue background color, white text color, and 7px border radius.
   - Also inside the group, add a "Heading" block for the phone number with the specified color, font size (20px), style (normal), and weight (600).

## Block Pattern:

```
<!-- wp:columns {"verticalAlignment":"center","align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"var:preset|spacing|70","bottom":"var:preset|spacing|70"},"blockGap":{"left":"70px"}}},"backgroundColor":"white"} -->
<div class="wp-block-columns alignwide are-vertically-aligned-center has-white-background-color has-background" style="margin-bottom:0;padding-top:var(--wp--preset--spacing--70);padding-bottom:var(--wp--preset--spacing--70)"><!-- wp:column {"verticalAlignment":"center","width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column is-vertically-aligned-center has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:cover {"url":"https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvbnM1Mzg5LWltYWdlLWt3dnlibHgxLmpwZw.jpg","id":null,"dimRatio":0,"minHeight":500,"isDark":false,"style":{"border":{"radius":{"topLeft":"100px","topRight":"0px","bottomRight":"100px","bottomLeft":"0px"}}},"layout":{"type":"constrained"}} -->
<div class="wp-block-cover is-light" style="border-top-left-radius:100px;border-top-right-radius:0px;border-bottom-left-radius:0px;border-bottom-right-radius:100px;min-height:500px"><span aria-hidden="true" class="wp-block-cover__background has-background-dim-0 has-background-dim"></span><img class="wp-block-cover__image-background" alt="" src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvbnM1Mzg5LWltYWdlLWt3dnlibHgxLmpwZw.jpg" data-object-fit="cover" /><div class="wp-block-cover__inner-container"><!-- wp:paragraph {"align":"center","placeholder":"Write title…","fontSize":"large"} -->
<p class="has-text-align-center has-large-font-size"></p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:cover --></div>
<!-- /wp:column -->

<!-- wp:column {"verticalAlignment":"center","width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"var:preset|spacing|30"},"border":{"width":"0px","style":"none"}}} -->
<div class="wp-block-column is-vertically-aligned-center has-text-color has-link-color" style="border-style:none;border-width:0px;color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:heading {"textAlign":"left","style":{"typography":{"fontStyle":"normal","fontWeight":"600","textTransform":"uppercase","fontSize":"14px","letterSpacing":"2px"},"elements":{"link":{"color":{"text":"var:preset|color|vivid-cyan-blue"}}}},"textColor":"vivid-cyan-blue"} -->
<h2 class="wp-block-heading has-text-align-left has-vivid-cyan-blue-color has-text-color has-link-color" style="font-size:14px;font-style:normal;font-weight:600;letter-spacing:2px;text-transform:uppercase">Our Story</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"40px","lineHeight":"1.2"}}} -->
<h3 class="wp-block-heading" style="font-size:40px;font-style:normal;font-weight:600;line-height:1.2">Integrating AI into education that impact society.</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"},"spacing":{"margin":{"top":"30px"}}}} -->
<p class="has-text-color has-link-color" style="color:#666565;margin-top:30px;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress allows users to create and edit their website more efficiently and with more control. It enables users to create unique and custom designs without needing to have advanced coding skills.</p>
<!-- /wp:paragraph -->

<!-- wp:group {"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button {"backgroundColor":"vivid-cyan-blue","textColor":"white","style":{"border":{"radius":"7px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-background-color has-text-color has-background has-link-color wp-element-button" style="border-radius:7px">Learn More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons -->

<!-- wp:heading {"style":{"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"},"elements":{"link":{"color":{"text":"var:preset|color|vivid-cyan-blue"}}}},"textColor":"vivid-cyan-blue"} -->
<h2 class="wp-block-heading has-vivid-cyan-blue-color has-text-color has-link-color" style="font-size:20px;font-style:normal;font-weight:600">+1 (012) 345-6789</h2>
<!-- /wp:heading --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Banner Section

## PURPOSE:

The purpose of this block layout is to create an engaging hero section or landing page to welcome visitors to a website about website building services. It aims to grab attention, communicate the key value proposition, and encourage visitors to take action.

## DESCRIPTION:

The layout features a full-width background image with a dark purple-to-blue gradient overlay, creating an eye-catching and immersive visual. Centered on top is a large, bold headline welcoming visitors to "a new era of website building". Below that is a brief paragraph of body text providing a high-level overview of the services.

At the bottom are two prominent call-to-action buttons - one to "Request Quote" with a white background and black text, and the other to "Schedule Quick Call" with a transparent background and white text/border. The buttons have rounded corners and uppercase text.

Overall, the layout is designed to create visual interest, quickly convey the core offering and value prop, and drive visitor action through the CTA buttons - all in an above-the-fold hero section.

## INSTRUCTIONS:

1. Add a Columns block and set it to full width alignment. Remove the bottom margin and all padding.
2. Inside the columns block, add a single Column. Set the text and link color to black, background to white, 1px cyan-bluish-gray border, and remove padding on all sides.
3. Inside the column, add a Cover block. Set a background image, 90% dim ratio, 700px min height, and a vivid-cyan-blue to vivid-purple gradient.
4. Inside the Cover block, add a centered Heading block with the welcome message. Set it to H1, 58px, bold, and 1.3 line height.
5. Below the heading, add a centered Paragraph block with the body text. Set the text and link color to light gray.
6. Below the paragraph, add a Buttons block with two buttons inside, centered horizontally. Set 45px top margin, 16px text, normal weight, and uppercase.
7. Style the first "Request Quote" button with white background, black text, 5px radius, 2px white border, and 20px top/bottom + 30px left/right padding.
8. Style the second "Schedule Quick Call" button with a transparent background, white text and border, 5px radius, 2px border, and 20px/30px padding.

## Block Pattern:

```
<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"0","bottom":"0"},"blockGap":{"top":"0","left":"0"}}}} -->
<div class="wp-block-columns alignwide" style="margin-bottom:0;padding-top:0;padding-bottom:0"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0px","right":"0px","bottom":"0px","left":"0px"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:0px;padding-right:0px;padding-bottom:0px;padding-left:0px"><!-- wp:cover {"url":"https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvcHg2MzQyODktaW1hZ2Uta3d2eG1paW4uanBn.jpg","dimRatio":90,"minHeight":700,"gradient":"vivid-cyan-blue-to-vivid-purple","layout":{"type":"constrained"}} -->
<div class="wp-block-cover" style="min-height:700px"><span aria-hidden="true" class="wp-block-cover__background has-background-dim-90 has-background-dim wp-block-cover__gradient-background has-background-gradient has-vivid-cyan-blue-to-vivid-purple-gradient-background"></span><img class="wp-block-cover__image-background" alt="" src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvcHg2MzQyODktaW1hZ2Uta3d2eG1paW4uanBn.jpg" data-object-fit="cover" /><div class="wp-block-cover__inner-container"><!-- wp:heading {"textAlign":"center","level":1,"style":{"typography":{"fontSize":"58px","fontStyle":"normal","fontWeight":"700","lineHeight":"1.3"}}} -->
<h1 class="wp-block-heading has-text-align-center" style="font-size:58px;font-style:normal;font-weight:700;line-height:1.3">Welcome to  New era of Website Building.</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#e5e8ea"}}},"color":{"text":"#e5e8ea"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#e5e8ea">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"center"},"style":{"spacing":{"blockGap":"var:preset|spacing|30","margin":{"top":"45px"}},"typography":{"fontSize":"16px","fontStyle":"normal","fontWeight":"600","textTransform":"uppercase"}}} -->
<div class="wp-block-buttons has-custom-font-size" style="margin-top:45px;font-size:16px;font-style:normal;font-weight:600;text-transform:uppercase"><!-- wp:button {"backgroundColor":"white","textColor":"black","style":{"border":{"radius":"5px","width":"2px"},"spacing":{"padding":{"left":"30px","right":"30px","top":"20px","bottom":"20px"}},"elements":{"link":{"color":{"text":"var:preset|color|black"}}}},"borderColor":"white"} -->
<div class="wp-block-button"><a class="wp-block-button__link has-black-color has-white-background-color has-text-color has-background has-link-color has-border-color has-white-border-color wp-element-button" style="border-width:2px;border-radius:5px;padding-top:20px;padding-right:30px;padding-bottom:20px;padding-left:30px">Request Quote</a></div>
<!-- /wp:button -->

<!-- wp:button {"textColor":"white","style":{"border":{"radius":"5px","width":"2px"},"spacing":{"padding":{"left":"30px","right":"30px","top":"20px","bottom":"20px"}},"color":{"background":"#ffffff00"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-text-color has-background has-link-color wp-element-button" style="border-width:2px;border-radius:5px;background-color:#ffffff00;padding-top:20px;padding-right:30px;padding-bottom:20px;padding-left:30px">Schedule Quick Call</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div></div>
<!-- /wp:cover --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Contact Us

## PURPOSE:

The purpose of this layout is to provide contact information and location details for a business in an attractive, easy-to-read format. It allows site visitors to quickly find key information for getting in touch with the business.

## DESCRIPTION:

The layout features a two-column design with a black background and white text for high contrast and readability.

The left column contains the heading "Keep in Touch" followed by a short paragraph of placeholder text. Below that are two sections, one for each business location, with the location name, address, phone number, and email.

The right column contains a map image showing the geographic area of Boston. This helps provide visual context for where the business locations are situated.

The use of ample white space, clear hierarchy in the headings and text, and visual balance between the two columns creates an organized, professional look.

## INSTRUCTIONS:

1. Add a Group block and set it to full width alignment. In the block settings, add padding of 40px on all sides, a black background color, and white text color.

2. Inside the Group block, add a Columns block with center vertical alignment. Set the block spacing to 50px gaps.

3. In the left column, add a Heading block with Heading 3 size. Enter "Keep in Touch". Set the font style to normal and font weight to 500.

4. Below the heading, add a Paragraph block with the placeholder text. Set the text color to #bdbdbd gray.

5. Add another Group block and give it 30px top padding. Make it a flex container with no wrap.

6. Inside that group, add another Group block with vertical orientation and these styles: 0 padding, 1rem gap between blocks.

7. Inside this new group, add a Heading block for the first location name. Make it H3 with 24px size, normal style, 500 weight.

8. Add 3 Paragraph blocks below it with the address, phone, and email. Set text color to #bdbdbd gray.

9. Duplicate the location group, change the heading to Location 2, and update the address/phone/email.

10. In the right column, add an Image block and insert the Boston map image at full size, not linked.

11. Preview the layout and make any final spacing, font size, or color adjustments in the block settings as needed.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"spacing":{"padding":{"top":"var:preset|spacing|40","right":"var:preset|spacing|40","bottom":"var:preset|spacing|40","left":"var:preset|spacing|40"}}},"backgroundColor":"black","textColor":"white","layout":{"type":"constrained","contentSize":"100%"}} -->
<div class="wp-block-group alignfull has-white-color has-black-background-color has-text-color has-background" style="padding-top:var(--wp--preset--spacing--40);padding-right:var(--wp--preset--spacing--40);padding-bottom:var(--wp--preset--spacing--40);padding-left:var(--wp--preset--spacing--40)"><!-- wp:columns {"verticalAlignment":"center","style":{"spacing":{"blockGap":{"top":"var:preset|spacing|50","left":"var:preset|spacing|50"}}}} -->
<div class="wp-block-columns are-vertically-aligned-center"><!-- wp:column {"verticalAlignment":"center"} -->
<div class="wp-block-column is-vertically-aligned-center"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"500"}}} -->
<h3 class="wp-block-heading" style="font-style:normal;font-weight:500">Keep in Touch</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">Lorem ipsum&nbsp;is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
<!-- /wp:paragraph -->

<!-- wp:group {"style":{"spacing":{"blockGap":"var:preset|spacing|50","padding":{"top":"var:preset|spacing|30"}}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group" style="padding-top:var(--wp--preset--spacing--30)"><!-- wp:group {"style":{"spacing":{"blockGap":"1rem","padding":{"top":"0","right":"0","bottom":"0","left":"0"}}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group" style="padding-top:0;padding-right:0;padding-bottom:0;padding-left:0"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"500","fontSize":"24px"}}} -->
<h3 class="wp-block-heading" style="font-size:24px;font-style:normal;font-weight:500">Location 1</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">Your Business Location -1,<br>Street, State, Country</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">+1 (012) 345-6789</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">email@yoursite.com</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"1rem","padding":{"top":"0","right":"0","bottom":"0","left":"0"}}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group" style="padding-top:0;padding-right:0;padding-bottom:0;padding-left:0"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"500","fontSize":"24px"}}} -->
<h3 class="wp-block-heading" style="font-size:24px;font-style:normal;font-weight:500">Location 2</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">Your Business Location -2,<br>Street, State, Country</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">+1 (012) 345-6789</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"color":{"text":"#bdbdbd"}}} -->
<p class="has-text-color" style="color:#bdbdbd">email@yoursite.com</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"verticalAlignment":"center"} -->
<div class="wp-block-column is-vertically-aligned-center"><!-- wp:image {"id":null,"sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvbnMyMjE5NS1pbWFnZS1rd3Z3bTI1aC5qcGc.jpg" alt="" /></figure>
<!-- /wp:image --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->
```

======

# Counter Stats Section

## PURPOSE:

The purpose of this layout is to highlight and showcase impressive statistics or metrics related to a company or organization, likely to build trust and credibility with website visitors. By prominently displaying numbers around things like years of experience, projects completed, team size, and satisfied customers, it helps convince potential clients that the company is well-established and capable.

## DESCRIPTION:

The layout consists of a heading "Let our number speaks" followed by four equal-width columns. Each column contains a large bolded number statistic and a label underneath clarifying what the number represents. The four metrics shown are:

- 10+ Years in Industry
- 100+ Projects Done
- 50+ Expert Teams
- 1000+ Happy Customers
  The numbers use a purple color while the labels are in a dark gray. The entire section has a white background and some vertical padding.

## INSTRUCTIONS:

To recreate this layout using the provided WordPress block pattern code:

1. Add a Group block and in its settings, apply 60px top padding. Inside the Group block:

2. Add a Heading block, set its text to "Let our number speaks", align center, and style 20px font size, normal style, and 600 weight.

3. Below the Group block, add a Columns block. Set it to wide width, top/bottom margins of 20px/0, 60px bottom padding, and a white background color.

4. Inside the Columns block, add 4 Column blocks.

5. Inside each Column block:

   - Add a Heading block, set content to the statistic number (10+, 100+, 50+, 1000+), set level to H1, align center, and style with 64px font size, normal style, 700 weight, 25px top margin, and #4940e9 text color.
   - Add a Paragraph block, set content to the statistic label, align center, and style with 18px font size and #59595b text color.

6. For each Column block, apply these styles: 0 padding on all sides, 8px block spacing, white background color, #000000 text color.

7. Publish or preview the page to see the completed "Let our number speaks" statistics layout.

## Block Pattern

```
<!-- wp:group {"style":{"spacing":{"padding":{"top":"60px"}}},"layout":{"type":"constrained"}} -->
<div class="wp-block-group" style="padding-top:60px"><!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"}}} -->
<h2 class="wp-block-heading has-text-align-center" style="font-size:20px;font-style:normal;font-weight:600">Let our number speaks</h2>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"top":"20px","bottom":"0"},"padding":{"bottom":"60px"}}},"backgroundColor":"white"} -->
<div class="wp-block-columns alignwide has-white-background-color has-background" style="margin-top:20px;margin-bottom:0;padding-bottom:60px"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:heading {"textAlign":"center","level":1,"style":{"typography":{"fontSize":"64px","fontStyle":"normal","fontWeight":"700"},"spacing":{"margin":{"top":"25px"}},"elements":{"link":{"color":{"text":"#4940e9"}}},"color":{"text":"#4940e9"}}} -->
<h1 class="wp-block-heading has-text-align-center has-text-color has-link-color" style="color:#4940e9;margin-top:25px;font-size:64px;font-style:normal;font-weight:700">10+</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"18px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:18px">Years in Industry</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:heading {"textAlign":"center","level":1,"style":{"typography":{"fontSize":"64px","fontStyle":"normal","fontWeight":"700"},"spacing":{"margin":{"top":"25px"}},"elements":{"link":{"color":{"text":"#4940e9"}}},"color":{"text":"#4940e9"}}} -->
<h1 class="wp-block-heading has-text-align-center has-text-color has-link-color" style="color:#4940e9;margin-top:25px;font-size:64px;font-style:normal;font-weight:700">100+</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"18px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:18px">Projects Done</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:heading {"textAlign":"center","level":1,"style":{"typography":{"fontSize":"64px","fontStyle":"normal","fontWeight":"700"},"spacing":{"margin":{"top":"25px"}},"elements":{"link":{"color":{"text":"#4940e9"}}},"color":{"text":"#4940e9"}}} -->
<h1 class="wp-block-heading has-text-align-center has-text-color has-link-color" style="color:#4940e9;margin-top:25px;font-size:64px;font-style:normal;font-weight:700">50+</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"18px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:18px">Expert Teams</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:heading {"textAlign":"center","level":1,"style":{"typography":{"fontSize":"64px","fontStyle":"normal","fontWeight":"700"},"spacing":{"margin":{"top":"25px"}},"elements":{"link":{"color":{"text":"#4940e9"}}},"color":{"text":"#4940e9"}}} -->
<h1 class="wp-block-heading has-text-align-center has-text-color has-link-color" style="color:#4940e9;margin-top:25px;font-size:64px;font-style:normal;font-weight:700">1000+</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"18px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:18px">Happy Customers</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# FAQ

## PURPOSE:

The purpose of this block pattern layout is to provide a visually appealing FAQ section for a WordPress website. It allows site owners to easily add frequently asked questions and answers in an organized, easy-to-read format.

## DESCRIPTION:

The FAQ block pattern consists of a two-column layout with a light gray background. The left column, taking up 40% of the width, contains the "FAQ" heading and a short description. The right column (60% width) lists out multiple questions and answers. Each question uses a larger, bold font as a heading (H3), while the answers appear in a smaller, lighter font below.

The questions and answers are separated into their own groups with vertical spacing between them for better readability. The text colors are dark gray for the questions and a lighter gray for the answers, providing good contrast.

## INSTRUCTIONS:

1. Insert a Columns block and set it to wide width alignment. In the block settings, set the bottom margin to 0, top/bottom padding to 70px, left block spacing to 60px, and the background color to #f7f7f7 (light gray).

2. In the left column, set the width to 40% and text/link color to black (#000000). Add a Heading block, choose Heading 2, and enter "FAQ". Style the heading with normal font style, 600 font weight, uppercase transform, and large font size.

3. Below the heading, add a Paragraph block and enter the FAQ intro text. Set the text alignment to left, text and link color to #8c8c8c (gray), and line height to 1.6.

4. In the right column, set the width to 60%, text and link color to black, padding on all sides to 0, and block spacing to 50px.

5. For each question and answer pair:

   - Add a Group block and set its inner block spacing to 20px with vertical orientation.
   - Inside the group, add a Heading block (H3) with the question text. Set font size to 20px, font style to normal, and font weight to 700 (bold).
   - Below the question, add a Paragraph block with the answer text. Set text and link color to #666565, font style to normal, font weight to 300, and line height to 1.5.

6. Repeat step 5 for each additional FAQ question and answer.

7. Save the page or post with the completed FAQ section.

## Block Pattern

```
<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"var:preset|spacing|70","bottom":"var:preset|spacing|70"},"blockGap":{"left":"60px"}},"color":{"background":"#f7f7f7"}}} -->
<div class="wp-block-columns alignwide has-background" style="background-color:#f7f7f7;margin-bottom:0;padding-top:var(--wp--preset--spacing--70);padding-bottom:var(--wp--preset--spacing--70)"><!-- wp:column {"width":"40%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:40%"><!-- wp:heading {"textAlign":"left","style":{"typography":{"fontStyle":"normal","fontWeight":"600","textTransform":"uppercase"}},"fontSize":"large"} -->
<h2 class="wp-block-heading has-text-align-left has-large-font-size" style="font-style:normal;font-weight:600;text-transform:uppercase">FAQ</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#8c8c8c"}}},"color":{"text":"#8c8c8c"},"typography":{"lineHeight":"1.6"}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#8c8c8c;line-height:1.6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"60%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"50px"},"border":{"width":"0px","style":"none"}}} -->
<div class="wp-block-column has-text-color has-link-color" style="border-style:none;border-width:0px;color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:60%"><!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"20px"}}} -->
<h3 class="wp-block-heading" style="font-size:20px;font-style:normal;font-weight:700">What is Full Site Editing in WordPress?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress refers to a feature that allows users to create and edit their website’s entire layout, including the header, footer, and other structural elements, using a visual editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"20px"}}} -->
<h3 class="wp-block-heading" style="font-size:20px;font-style:normal;font-weight:700">How do I enable Full Site Editing in WordPress?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">To enable Full Site Editing in WordPress, you need to ensure that you are using a compatible WordPress theme that supports Full Site Editing. You will also need to install the latest version of WordPress and enable the Gutenberg editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"20px"}}} -->
<h3 class="wp-block-heading" style="font-size:20px;font-style:normal;font-weight:700">What are some popular WordPress themes that support Full Site Editing?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">Some popular WordPress themes that support Full Site Editing include the FotaWP Theme, the Fota Speakes Theme, and the Fota Home Solutions Theme. These themes have built-in support for Full Site Editing, allowing users to create custom designs without needing to know how to code.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"20px"}}} -->
<h3 class="wp-block-heading" style="font-size:20px;font-style:normal;font-weight:700">What are the benefits of Full Site Editing in WordPress?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress allows users to create and edit their website more efficiently and with more control. It enables users to create unique and custom designs without needing to have advanced coding skills.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Featured Services Box

## PURPOSE:

The purpose of this layout is to showcase featured services offered by a company or business in an organized and visually appealing way on their website.

## DESCRIPTION:

The layout has a light gray background and is divided into two columns. The left column contains a heading "Featured Services", a short paragraph description, and a yellow button labeled "View All Services".

The right column contains 4 boxes arranged in a 2x2 grid, each representing a different service. The services shown are Web Development, Case Study, Research & Plan, and UI/UX Design. Each box has a centered icon, title, and brief description.

The entire section uses a consistent color scheme of black text, light gray background, and a pop of yellow for the button. The font sizes vary to create hierarchy, with the main heading being largest.

## INSTRUCTIONS:

1. Create a new Group block and apply the following settings:

   - Alignment: Full width
   - Text color: #87878b
   - Background color: #f9f9f9
   - Minimum height: 40vh
   - Top/bottom margin: 0
   - Padding: 90px top/bottom, 30px left/right
   - Block spacing: var:preset|spacing|30

2. Inside the Group block, add a Columns block with vertically center alignment and 60px gap between columns.

3. In the left column, set width to 40% and vertical alignment to center.

4. Inside the left column, add a Group block with 660px constrained content size.

5. In that Group block, add a Heading with text "Featured Services", left alignment, 32px size, 600 weight, and black text color.

6. Below the heading, add a Paragraph with the desired description, left aligned, #87878b text color, and 1.6 line height.

7. Add a Button block, apply #e4ab00 background color, white text color, 7px border radius, and 25px left/right & 15px top/bottom padding.

8. In the right column, set 60% width and 0 padding on all sides.

9. Inside the right column, add a Columns block with wide width, small font size, 20px gap between columns, and 25px top margin.

10. In the Columns block, create two columns each with 60% width.

11. In each of the 4 columns, add a Group block with 25px padding on all sides, 7px border radius, and white background color.

12. Inside each Group block:

    - Add an Image block, center aligned, resized to auto width and 60px height
    - Add a Heading with the service name, center aligned, 20px size, 600 weight, black color
    - Add a Paragraph with a brief description, center aligned, 16px font size

13. Repeat steps 9-12 to create the second row of service boxes.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"#87878b"}}},"spacing":{"padding":{"top":"90px","right":"30px","bottom":"90px","left":"30px"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":"40vh"},"color":{"text":"#87878b","background":"#f9f9f9"}},"className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-text-color has-background has-link-color" style="color:#87878b;background-color:#f9f9f9;min-height:40vh;margin-top:0;margin-bottom:0;padding-top:90px;padding-right:30px;padding-bottom:90px;padding-left:30px"><!-- wp:columns {"verticalAlignment":"center","style":{"spacing":{"blockGap":{"left":"60px"}}}} -->
<div class="wp-block-columns are-vertically-aligned-center"><!-- wp:column {"verticalAlignment":"center","width":"40%"} -->
<div class="wp-block-column is-vertically-aligned-center" style="flex-basis:40%"><!-- wp:group {"layout":{"type":"constrained","contentSize":"660px"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"32px"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-left has-black-color has-text-color has-link-color" style="font-size:32px;font-style:normal;font-weight:600">Featured Services</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#87878b"}}},"color":{"text":"#87878b"},"typography":{"lineHeight":"1.6"}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#87878b;line-height:1.6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button {"textColor":"white","style":{"color":{"background":"#e4ab00"},"border":{"radius":"7px"},"spacing":{"padding":{"left":"25px","right":"25px","top":"15px","bottom":"15px"}},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-text-color has-background has-link-color wp-element-button" style="border-radius:7px;background-color:#e4ab00;padding-top:15px;padding-right:25px;padding-bottom:15px;padding-left:25px">View All Services</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"verticalAlignment":"center","width":"60%","style":{"spacing":{"blockGap":"0","padding":{"top":"0","bottom":"0","left":"0","right":"0"}}}} -->
<div class="wp-block-column is-vertically-aligned-center" style="padding-top:0;padding-right:0;padding-bottom:0;padding-left:0;flex-basis:60%"><!-- wp:columns {"align":"wide","style":{"spacing":{"blockGap":{"left":"20px"}}},"fontSize":"small"} -->
<div class="wp-block-columns alignwide has-small-font-size"><!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:group {"style":{"spacing":{"padding":{"top":"25px","bottom":"25px","left":"25px","right":"25px"}},"border":{"radius":"7px"}},"backgroundColor":"white","layout":{"type":"constrained"}} -->
<div class="wp-block-group has-white-background-color has-background" style="border-radius:7px;padding-top:25px;padding-right:25px;padding-bottom:25px;padding-left:25px"><!-- wp:image {"align":"center","width":"auto","height":"60px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0xNzUtcC5wbmc.png" alt="" style="width:auto;height:60px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-center has-black-color has-text-color has-link-color" style="font-size:20px;font-style:normal;font-weight:600">Web Development</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:group {"style":{"spacing":{"padding":{"top":"25px","bottom":"25px","left":"25px","right":"25px"}},"border":{"radius":"7px"}},"backgroundColor":"white","layout":{"type":"constrained"}} -->
<div class="wp-block-group has-white-background-color has-background" style="border-radius:7px;padding-top:25px;padding-right:25px;padding-bottom:25px;padding-left:25px"><!-- wp:image {"align":"center","width":"auto","height":"60px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0xNzUtcC5wbmc.png" alt="" style="width:auto;height:60px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-center has-black-color has-text-color has-link-color" style="font-size:20px;font-style:normal;font-weight:600">Case Study</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"top":"25px"},"blockGap":{"left":"20px"}}},"fontSize":"small"} -->
<div class="wp-block-columns alignwide has-small-font-size" style="margin-top:25px"><!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:group {"style":{"spacing":{"padding":{"top":"25px","bottom":"25px","left":"25px","right":"25px"}},"border":{"radius":"7px"}},"backgroundColor":"white","layout":{"type":"constrained"}} -->
<div class="wp-block-group has-white-background-color has-background" style="border-radius:7px;padding-top:25px;padding-right:25px;padding-bottom:25px;padding-left:25px"><!-- wp:image {"align":"center","width":"auto","height":"60px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0xNzUtcC5wbmc.png" alt="" style="width:auto;height:60px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-center has-black-color has-text-color has-link-color" style="font-size:20px;font-style:normal;font-weight:600">Research &amp; Plan</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:group {"style":{"spacing":{"padding":{"top":"25px","bottom":"25px","left":"25px","right":"25px"}},"border":{"radius":"7px"}},"backgroundColor":"white","layout":{"type":"constrained"}} -->
<div class="wp-block-group has-white-background-color has-background" style="border-radius:7px;padding-top:25px;padding-right:25px;padding-bottom:25px;padding-left:25px"><!-- wp:image {"align":"center","width":"auto","height":"60px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0xNzUtcC5wbmc.png" alt="" style="width:auto;height:60px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-center has-black-color has-text-color has-link-color" style="font-size:20px;font-style:normal;font-weight:600">UI/UX Design</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->
```

======

# Features Block

## PURPOSE:

The purpose of this layout is to showcase featured services offered by a company or website. It aims to highlight key benefits and features in an organized, visually appealing way to convince visitors of the value provided.

## DESCRIPTION:

The layout has a full-width purple background section with white text. The heading "Featured Services" is in large font on the left. There are two columns below, each containing two service highlight boxes.

Each service box has a bold white heading and a short paragraph description in a lighter gray color. The four services highlighted are:

1. 100% Optimized
2. 100% Track Record
3. SEO Friendly
4. Light Weight

The consistent formatting and spacing of the service boxes makes the information easy to read and digest at a glance. The high-contrast colors make the content stand out.

## INSTRUCTIONS:

To recreate this Featured Services layout using the provided WordPress block pattern code:

1. Add a Full Width Group block and apply the following settings:

- Set background color to #3f39b8
- Set text color to #87878b
- Set minimum height to 40vh
- Add 60px top/bottom padding and 40px left/right padding

2. Inside the Group block, add a Heading block with "Featured Services" and style it with 44px white text.

3. Below the heading, add a Paragraph block with some intro text and style it with #e4e3e3 color.

4. Add a Columns block below with 2 columns.

5. Inside each column, add a Group block. Inside each Group block:

- Add a Heading block for the service name, styled with 30px bold white text
- Add a Paragraph block with the service description, styled with #e4e3e3 color

6. Set margin and padding as specified in the code to achieve the desired vertical and horizontal spacing between elements.

7. Duplicate the 2-column Columns block to show 4 services total.

8. Save and publish the page. The Featured Services section should now match the layout in the image.

## Block Pattern:

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"#87878b"}}},"spacing":{"padding":{"right":"40px","left":"40px","top":"60px","bottom":"60px"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":"40vh"},"color":{"text":"#87878b","background":"#3f39b8"}},"className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-text-color has-background has-link-color" style="color:#87878b;background-color:#3f39b8;min-height:40vh;margin-top:0;margin-bottom:0;padding-top:60px;padding-right:40px;padding-bottom:60px;padding-left:40px"><!-- wp:group {"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:columns -->
<div class="wp-block-columns"><!-- wp:column {"width":"66.66%"} -->
<div class="wp-block-column" style="flex-basis:66.66%"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"44px"}},"textColor":"white"} -->
<h2 class="wp-block-heading has-text-align-left has-white-color has-text-color has-link-color" style="font-size:44px;font-style:normal;font-weight:600">Featured Services</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#e4e3e3"}}},"color":{"text":"#e4e3e3"},"typography":{"lineHeight":"1.6"}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#e4e3e3;line-height:1.6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"33.33%"} -->
<div class="wp-block-column" style="flex-basis:33.33%"></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"var:preset|spacing|50","bottom":"var:preset|spacing|40"},"blockGap":{"left":"80px"}}}} -->
<div class="wp-block-columns alignwide" style="margin-bottom:0;padding-top:var(--wp--preset--spacing--50);padding-bottom:var(--wp--preset--spacing--40)"><!-- wp:column {"width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"textColor":"white"} -->
<h3 class="wp-block-heading has-white-color has-text-color has-link-color" style="font-size:30px;font-style:normal;font-weight:700">100% Optimized</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#e4e3e3"}}},"color":{"text":"#e4e3e3"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#e4e3e3;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress refers to a feature that allows users to create and edit their website’s entire layout, including the header, footer, and other structural elements, using a visual editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"textColor":"white"} -->
<h3 class="wp-block-heading has-white-color has-text-color has-link-color" style="font-size:30px;font-style:normal;font-weight:700">100% Track Record</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#e4e3e3"}}},"color":{"text":"#e4e3e3"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#e4e3e3;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress refers to a feature that allows users to create and edit their website’s entire layout, including the header, footer, and other structural elements, using a visual editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"var:preset|spacing|20","bottom":"var:preset|spacing|40"},"blockGap":{"left":"80px"}}}} -->
<div class="wp-block-columns alignwide" style="margin-bottom:0;padding-top:var(--wp--preset--spacing--20);padding-bottom:var(--wp--preset--spacing--40)"><!-- wp:column {"width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"textColor":"white"} -->
<h3 class="wp-block-heading has-white-color has-text-color has-link-color" style="font-size:30px;font-style:normal;font-weight:700">SEO Friendly</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#e4e3e3"}}},"color":{"text":"#e4e3e3"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#e4e3e3;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress refers to a feature that allows users to create and edit their website’s entire layout, including the header, footer, and other structural elements, using a visual editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"50%","style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"}}}} -->
<div class="wp-block-column has-text-color has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em;flex-basis:50%"><!-- wp:group {"style":{"spacing":{"blockGap":"20px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"textColor":"white"} -->
<h3 class="wp-block-heading has-white-color has-text-color has-link-color" style="font-size:30px;font-style:normal;font-weight:700">Light Weight</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#e4e3e3"}}},"color":{"text":"#e4e3e3"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#e4e3e3;font-style:normal;font-weight:300;line-height:1.5">Full Site Editing in WordPress refers to a feature that allows users to create and edit their website’s entire layout, including the header, footer, and other structural elements, using a visual editor.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->
```

======

# Footer Minimal

## PURPOSE:

The purpose of this layout is to create a simple footer section for a website. It displays the company logo, contact information, a copyright notice, and social media links against a black background.

## DESCRIPTION:

The image shows a footer layout with a black background and white text. It is divided into two main sections:

1. The top section centers the company logo as large text, with the company's physical address, phone number, and email displayed below in smaller text.

2. The bottom section contains a horizontal line separator, followed by a centered copyright notice on the left side and a row of social media icons on the right side. The social media icons include WordPress, Behance, GitHub, Facebook, Twitch, and Twitter.

The layout has ample vertical padding and is designed to span the full width of the page. The text sizing and spacing helps create a clear visual hierarchy.

## INSTRUCTIONS:

To recreate this footer layout using the provided WordPress block pattern code:

1. Add a Group block and set it to full width alignment. Configure its background color to black, text color to white, minimum height to 40vh, and add vertical padding.

2. Inside the Group block, add a Columns block with wide width and small font size.

3. Inside the Columns block, add a single Column.

4. Inside the Column, add another Group block with vertical orientation and center justification.

5. Add a centered Heading block inside this Group with the company logo text. Set its font size to 60px and font weight to bold.

6. Below the Heading, add three Paragraph blocks to display the address, phone number and email. Center align each and set their font sizes to 16px.

7. After the Columns block, add another Group block with wide width alignment. Give it a 1px top border in an off-black color. Set its top margin and top padding, and configure it to display its inner blocks as a justified row with wrapped flow.

8. Inside this Group block, add a centered Paragraph for the copyright text and set it to small font size.

9. Next to the copyright, add a Social Links block, set to center justify its icons and add small spacing between them.

10. Configure the Social Links with the desired social profile URLs for WordPress, Behance, GitHub, Facebook, Twitch and Twitter.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"var:preset|spacing|60","right":"var:preset|spacing|40","bottom":"30px","left":"var:preset|spacing|40"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":"40vh"}},"backgroundColor":"black","textColor":"white","className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-white-color has-black-background-color has-text-color has-background has-link-color" style="min-height:40vh;margin-top:0;margin-bottom:0;padding-top:var(--wp--preset--spacing--60);padding-right:var(--wp--preset--spacing--40);padding-bottom:30px;padding-left:var(--wp--preset--spacing--40)"><!-- wp:columns {"align":"wide","fontSize":"small"} -->
<div class="wp-block-columns alignwide has-small-font-size"><!-- wp:column {"width":""} -->
<div class="wp-block-column"><!-- wp:group {"layout":{"type":"flex","orientation":"vertical","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"60px","fontStyle":"normal","fontWeight":"700"}}} -->
<h2 class="wp-block-heading has-text-align-center" style="font-size:60px;font-style:normal;font-weight:700">LOGO</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px","lineHeight":"1.6"}}} -->
<p class="has-text-align-center" style="font-size:16px;line-height:1.6">12315 Mozell Club, Louisiana 90576, United States</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">+1 (012) 345-6789</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-center" style="font-size:16px">email@yoursite.com</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:group {"align":"wide","style":{"spacing":{"padding":{"top":"30px"},"margin":{"top":"40px"}},"border":{"top":{"color":"#1e1b1b","width":"1px"}}},"layout":{"type":"flex","justifyContent":"space-between","flexWrap":"wrap"}} -->
<div class="wp-block-group alignwide" style="border-top-color:#1e1b1b;border-top-width:1px;margin-top:40px;padding-top:30px"><!-- wp:paragraph {"align":"center","fontSize":"small"} -->
<p class="has-text-align-center has-small-font-size"> Proudly powered WordPress Design by CozyThemes</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"5px"}}},"layout":{"type":"flex","justifyContent":"center"}} -->
<ul class="wp-block-social-links"><!-- wp:social-link {"url":"#","service":"wordpress"} /-->

<!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"github"} /-->

<!-- wp:social-link {"url":"#","service":"facebook"} /-->

<!-- wp:social-link {"url":"#","service":"twitch"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->
```

======

# Footer

## PURPOSE:

The purpose of this layout is to create a footer section for a website that displays key company information, navigation links, social media icons, and a copyright notice. It provides visitors with easy access to important details and helps establish the site's branding and credibility.

## DESCRIPTION:

The footer layout has a black background with white text. It is divided into three main columns:

1. The left column contains the company logo, address, phone number, email, and social media icons.

2. The middle column has a "Company" heading with links to pages like About Us, Blog, Services, and Career.

3. The right column has a "Services" heading with links to the company's offerings like Web Development, Digital Marketing, SEO Services, and UI/UX Design.

Below the three columns is a centered copyright notice.

## INSTRUCTIONS:

1. In your WordPress editor, create a new Group block and apply the following settings:

   - Set full width alignment
   - Add black background color
   - Set white text color
   - Adjust padding and minimum height as needed

2. Inside the Group block, add a Columns block and configure it to have 3 columns.

3. In the left column, add your logo using a Heading block. Below that, add the company address, phone, and email using Paragraph blocks. Finally, add social media links using the Social Links block.

4. In the middle column, add a Heading block for the "Company" section. Below that, add a Group block with Paragraph blocks inside, each containing a link to the relevant page (About Us, Blog, Services, Career).

5. Repeat step 4 for the right column, using "Services" as the heading and adding links to the company's offerings.

6. After the Columns block, add a Group block for the copyright notice. Inside, add a centered Paragraph block with the copyright text.

7. Adjust colors, font sizes, spacing and other styles throughout to match the original layout.

8. Save your changes and you should now have a footer layout closely resembling the one in the image.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"var:preset|spacing|60","right":"var:preset|spacing|40","bottom":"30px","left":"var:preset|spacing|40"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":"40vh"}},"backgroundColor":"black","textColor":"white","className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-white-color has-black-background-color has-text-color has-background has-link-color" style="min-height:40vh;margin-top:0;margin-bottom:0;padding-top:var(--wp--preset--spacing--60);padding-right:var(--wp--preset--spacing--40);padding-bottom:30px;padding-left:var(--wp--preset--spacing--40)"><!-- wp:columns {"align":"wide","fontSize":"small"} -->
<div class="wp-block-columns alignwide has-small-font-size"><!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:columns -->
<div class="wp-block-columns"><!-- wp:column {"width":"50%"} -->
<div class="wp-block-column" style="flex-basis:50%"><!-- wp:heading {"textAlign":"left","style":{"typography":{"fontSize":"30px","fontStyle":"normal","fontWeight":"700"}}} -->
<h2 class="wp-block-heading has-text-align-left" style="font-size:30px;font-style:normal;font-weight:700">LOGO</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"typography":{"fontSize":"16px","lineHeight":"1.6"}}} -->
<p class="has-text-align-left" style="font-size:16px;line-height:1.6">12315 Mozell Club, Louisiana 90576, United States</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"typography":{"fontSize":"16px"}}} -->
<p style="font-size:16px">+1 (012) 345-6789</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"typography":{"fontSize":"16px"}}} -->
<p style="font-size:16px">email@yoursite.com</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"5px"}}}} -->
<ul class="wp-block-social-links"><!-- wp:social-link {"url":"#","service":"wordpress"} /-->

<!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"github"} /-->

<!-- wp:social-link {"url":"#","service":"facebook"} /-->

<!-- wp:social-link {"url":"#","service":"twitch"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"50%"} -->
<div class="wp-block-column" style="flex-basis:50%"></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"><!-- wp:heading {"textAlign":"left","level":5,"style":{"typography":{"fontSize":"18px","fontStyle":"normal","fontWeight":"600"}}} -->
<h5 class="wp-block-heading has-text-align-left" style="font-size:18px;font-style:normal;font-weight:600">Company</h5>
<!-- /wp:heading -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:paragraph -->
<p><a href="#">About Us</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">Blog</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">Services</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">Career</a></p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"><!-- wp:heading {"textAlign":"left","level":5,"style":{"typography":{"fontSize":"18px","fontStyle":"normal","fontWeight":"600"}}} -->
<h5 class="wp-block-heading has-text-align-left" style="font-size:18px;font-style:normal;font-weight:600">Services</h5>
<!-- /wp:heading -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:paragraph -->
<p><a href="#">Web Development</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">Digital Marketing</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">SEO Services</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="#">UI/UX Design</a></p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:group {"align":"wide","style":{"spacing":{"padding":{"top":"30px"},"margin":{"top":"40px"}},"border":{"top":{"color":"#1e1b1b","width":"1px"}}},"layout":{"type":"flex","justifyContent":"center","flexWrap":"wrap"}} -->
<div class="wp-block-group alignwide" style="border-top-color:#1e1b1b;border-top-width:1px;margin-top:40px;padding-top:30px"><!-- wp:paragraph {"align":"center","fontSize":"small"} -->
<p class="has-text-align-center has-small-font-size"> Proudly powered WordPress Design by CozyThemes</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->
```

======

# Header with Button

## PURPOSE:

The purpose of this layout is to create a responsive website header that includes a site logo, site title, navigation menu, and a "Schedule Call" button. This header layout provides a clean and professional design for a website.

## DESCRIPTION:

The layout consists of a white background header section with black text color. It is divided into two main parts:

1. Left side: Contains the site logo (placeholder image) and the site title.
2. Right side: Contains the navigation menu and a "Schedule Call" button.

The site logo is set to a fixed width of 60px. The site title uses a 24px font size and has a hover effect that changes its color to a vivid cyan blue.

The "Schedule Call" button has a vivid cyan blue to vivid purple gradient background, white text color, 16px font size, normal font style, 500 font weight, and a 6px border radius.

The layout is fully responsive and adjusts well to different screen sizes.

## INSTRUCTIONS:

1. Create a new block pattern in your WordPress theme or plugin.

2. Start with a Group block that has the following settings:

   - Align: Full width
   - Text color: Black
   - Background color: White
   - Padding: 20px top, 40px right, 20px bottom, 40px left
   - Margin: 0 top, 0 bottom
   - Block gap: 30px
   - Minimum height: Leave empty
   - Link color: Black

3. Inside the Group block, add another Group block with the following settings:

   - Align: Wide
   - Layout: Flex, space between, wrap
   - Border top: 0px, none

4. Within the second Group block, add two more Group blocks:

   - First Group block:
     - Layout: Flex, nowrap
     - Block gap: 15px
     - Add a Site Logo block with a width of 60px
     - Add a Site Title block with font size 24px, no text decoration, and a hover color of vivid cyan blue
   - Second Group block:
     - Layout: Flex, nowrap
     - Add a Navigation block with black text color
     - Add a Buttons block with layout flex and justify content right

5. Inside the Buttons block, add a Button block with the following settings:

   - Text color: White
   - Gradient background: Vivid cyan blue to vivid purple
   - Font size: 16px
   - Font style: Normal
   - Font weight: 500
   - Border radius: 6px
   - Button text: "Schedule Call"

6. Save the block pattern.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"spacing":{"padding":{"top":"20px","right":"var:preset|spacing|40","bottom":"20px","left":"var:preset|spacing|40"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":""}},"backgroundColor":"white","textColor":"black","className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-black-color has-white-background-color has-text-color has-background has-link-color" style="margin-top:0;margin-bottom:0;padding-top:20px;padding-right:var(--wp--preset--spacing--40);padding-bottom:20px;padding-left:var(--wp--preset--spacing--40)"><!-- wp:group {"align":"wide","style":{"border":{"top":{"width":"0px","style":"none"},"right":[],"bottom":[],"left":[]}},"layout":{"type":"flex","justifyContent":"space-between","flexWrap":"wrap"}} -->
<div class="wp-block-group alignwide" style="border-top-style:none;border-top-width:0px"><!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:site-logo {"width":60,"style":{"layout":{"selfStretch":"fixed","flexSize":"60px"}}} /-->

<!-- wp:site-title {"style":{"typography":{"textDecoration":"none","fontSize":"24px"},"elements":{"link":{"color":{"text":"var:preset|color|black"},":hover":{"color":{"text":"var:preset|color|vivid-cyan-blue"}}}}}} /--></div>
<!-- /wp:group -->

<!-- wp:group {"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:navigation {"textColor":"black"} /-->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"right"}} -->
<div class="wp-block-buttons"><!-- wp:button {"textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"typography":{"fontSize":"16px","fontStyle":"normal","fontWeight":"500"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"border":{"radius":"6px"}}} -->
<div class="wp-block-button has-custom-font-size" style="font-size:16px;font-style:normal;font-weight:500"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color wp-element-button" style="border-radius:6px">Schedule Call</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:group --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->
```

======

# Header

## PURPOSE:

The purpose of this layout is to create a simple website header or navigation bar with a logo, navigation menu, and social media links on a dark background.

## DESCRIPTION:

The layout consists of a full-width black bar with white text. It contains a logo on the left side, which is a level 2 heading that says "LOGO". To the right of the logo is a navigation menu. On the far right are social media icons linking to WordPress, Behance, GitHub, Facebook, Twitch, and Twitter profiles.

The layout uses flexbox to arrange the logo and navigation menu on one line, with space between them. The social icons are also laid out using flexbox and have a small gap between each icon.

## INSTRUCTIONS:

1. Create a new Group block and set it to full width alignment. In the block settings, set the background color to black and text color to white. Add padding of 20px top/bottom and 40px left/right. Set the minimum block height as needed.

2. Inside the Group block, add another Group block with wide width alignment. Enable flexbox and set it to display the child blocks as space-between, allowing them to wrap.

3. Inside the second Group block, add another Group block. Enable flexbox and disable wrap so the child blocks stay on one line.

4. Inside the third Group block, add a Heading block. Set the heading to level 2, align the text to center, and enter the logo text (e.g. "LOGO"). Style the heading with 32px font size, normal style, and bold 700 weight.

5. After the Heading block, add a Navigation block for the menu.

6. After the third Group block, add a Social Icons block. Set the block justification to left and add a small 5px gap between icons.

7. Add individual social link blocks inside the Social Icons block, setting the URL and service for each (WordPress, Behance, GitHub, Facebook, Twitch, Twitter).

8. Save the changes and the header layout is complete. The logo, menu and social icons will display on one line, with flexbox used to control positioning and spacing. The dark background and white text provide strong contrast.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"20px","right":"var:preset|spacing|40","bottom":"20px","left":"var:preset|spacing|40"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":""}},"backgroundColor":"black","textColor":"white","className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-white-color has-black-background-color has-text-color has-background has-link-color" style="margin-top:0;margin-bottom:0;padding-top:20px;padding-right:var(--wp--preset--spacing--40);padding-bottom:20px;padding-left:var(--wp--preset--spacing--40)"><!-- wp:group {"align":"wide","style":{"border":{"top":{"width":"0px","style":"none"},"right":[],"bottom":[],"left":[]}},"layout":{"type":"flex","justifyContent":"space-between","flexWrap":"wrap"}} -->
<div class="wp-block-group alignwide" style="border-top-style:none;border-top-width:0px"><!-- wp:group {"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"32px","fontStyle":"normal","fontWeight":"700"}}} -->
<h2 class="wp-block-heading has-text-align-center" style="font-size:32px;font-style:normal;font-weight:700">LOGO</h2>
<!-- /wp:heading -->

<!-- wp:navigation /--></div>
<!-- /wp:group -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"5px"}}},"layout":{"type":"flex","justifyContent":"left"}} -->
<ul class="wp-block-social-links"><!-- wp:social-link {"url":"#","service":"wordpress"} /-->

<!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"github"} /-->

<!-- wp:social-link {"url":"#","service":"facebook"} /-->

<!-- wp:social-link {"url":"#","service":"twitch"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->
```

======

# How It Works Block

## PURPOSE:

The purpose of this layout is to explain a simple 3-step process for how a service works. It provides an overview of the process at the top, followed by concise descriptions of each step below.

## DESCRIPTION:

The layout has a white background and uses a vertical column structure. At the top is an introductory section with a heading "How It Works" and a short paragraph providing an overview. Below this are three equal-width columns, each describing one step of the process. The step headings are numbered "1. Register", "2. Schedule Appointment", and "3. Meet". Each step has a brief paragraph description below the heading. The color scheme uses black for the headings and a gray color for the body text.

## INSTRUCTIONS:

1. Create a new Group block and set it to full width alignment. Apply white background color, gray text color, top/bottom padding of 60px, left/right padding of 30px, and minimum height of 40vh.

2. Inside the Group block, add a Columns block. Make the left column 66.66% width and leave the right column empty.

3. In the left column, add a Heading block for the "How It Works" title. Set its text alignment to left, color to black, font size to 44px, and font weight to 600.

4. Below the heading, add a Paragraph block for the overview text. Set its text alignment to left and line height to 1.6.

5. After the intro Group block, add a new Columns block and enable wide width alignment. Set the top margin to 60px and block gap to 60px.

6. Make this new Columns block have 3 equal columns.

7. In each column, add a Heading block for the step number and title (e.g. "1. Register"). Set the headings' text alignment to left, color to black, font size to 24px, and font weight to 600.

8. Below each step heading, add a Paragraph block for the step description and set its font size to 16px.

9. Repeat steps 7-8 for the remaining two columns, with the content for steps 2 and 3.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"elements":{"link":{"color":{"text":"#87878b"}}},"spacing":{"padding":{"top":"60px","right":"30px","bottom":"60px","left":"30px"},"margin":{"top":"0","bottom":"0"},"blockGap":"var:preset|spacing|30"},"dimensions":{"minHeight":"40vh"},"color":{"text":"#87878b"}},"backgroundColor":"white","className":"has-background-color","layout":{"type":"flex","orientation":"vertical","justifyContent":"stretch","verticalAlignment":"center"}} -->
<div class="wp-block-group alignfull has-background-color has-white-background-color has-text-color has-background has-link-color" style="color:#87878b;min-height:40vh;margin-top:0;margin-bottom:0;padding-top:60px;padding-right:30px;padding-bottom:60px;padding-left:30px"><!-- wp:group {"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:columns -->
<div class="wp-block-columns"><!-- wp:column {"width":"66.66%"} -->
<div class="wp-block-column" style="flex-basis:66.66%"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"44px"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-left has-black-color has-text-color has-link-color" style="font-size:44px;font-style:normal;font-weight:600">How It Works</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#87878b"}}},"color":{"text":"#87878b"},"typography":{"lineHeight":"1.6"}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#87878b;line-height:1.6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"33.33%"} -->
<div class="wp-block-column" style="flex-basis:33.33%"></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"top":"60px"},"blockGap":{"left":"60px"}}},"fontSize":"small"} -->
<div class="wp-block-columns alignwide has-small-font-size" style="margin-top:60px"><!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-left has-black-color has-text-color has-link-color" style="font-size:24px;font-style:normal;font-weight:600">1. Register</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-left" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-left has-black-color has-text-color has-link-color" style="font-size:24px;font-style:normal;font-weight:600">2. Schedule Appointment</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-left" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"60%"} -->
<div class="wp-block-column" style="flex-basis:60%"><!-- wp:heading {"textAlign":"left","style":{"elements":{"link":{"color":{"text":"var:preset|color|black"}}},"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"600"}},"textColor":"black"} -->
<h2 class="wp-block-heading has-text-align-left has-black-color has-text-color has-link-color" style="font-size:24px;font-style:normal;font-weight:600">3. Meet</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"typography":{"fontSize":"16px"}}} -->
<p class="has-text-align-left" style="font-size:16px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->
```

======

# Pricing Tables

## PURPOSE:

The purpose of this layout is to showcase a pricing table with two plan options - Personal and Agency. It allows potential customers to compare the features and pricing of the two plans side-by-side to help them choose the best option for their needs.

## DESCRIPTION:

The layout consists of a heading "PLAN & PRICING" with a short description underneath. Below that are two columns, each featuring a pricing plan.

The left column highlights the "Personal" plan, priced at $49.99. It includes a description of the plan, the price, and a list of featured inclusions like single site access, 1 year free support, 1GB free hosting, unmetered bandwidth, and 1 email account. There is a "GET THIS PACKAGE" button at the bottom.

The right column showcases the "Agency" plan, priced at $249.99. Similar to the Personal plan, it includes a description, price, and a list of features. The Agency plan offers single site access, 1 year free support, unlimited free hosting, unmetered bandwidth, and 100+ email accounts. It also has a "GET THIS PACKAGE" button.

The columns have a white background, are bordered, and use a consistent layout with heading styles, bullet points, and button styling.

## INSTRUCTIONS:

1. Add a Columns block and choose the two column layout. In the block settings, set the alignment to "wide" and add 0 bottom margin.

2. In the left column, add a Heading block for the section title "PLAN & PRICING". Style it with 600 font weight, large font size, and uppercase.

3. Below the heading, add a Paragraph block for the section description. Customize the text color and link color to match the design.

4. In the right column, add another Column block for the "Personal" plan.

5. Inside the "Personal" column, add Heading blocks for the plan name, description, and price. Style them based on the design.

6. Add a Group block below the price heading. Inside it, add multiple groups each containing an Image block (for the bullet point) and a Heading block for the feature text. Repeat for each feature.

7. Add a Buttons block aligned to the left below the feature list. Inside it, add a Button block with the "GET THIS PACKAGE" text, applying the color gradient background and other button styles.

8. Copy the entire right "Personal" plan column and paste it to create the "Agency" plan column. Update the plan name, description, price, and features based on the content in the image.

9. Fine-tune margins, padding, font sizes, colors, and other styles throughout to match the provided design screenshot.

## Block Pattern

```
<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"}}}} -->
<div class="wp-block-columns alignwide" style="margin-bottom:0"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"2em","bottom":"2em","left":"2em"}}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:2em;padding-right:2em;padding-bottom:2em;padding-left:2em"><!-- wp:heading {"textAlign":"left","style":{"typography":{"fontStyle":"normal","fontWeight":"600","textTransform":"uppercase"}},"fontSize":"large"} -->
<h2 class="wp-block-heading has-text-align-left has-large-font-size" style="font-style:normal;font-weight:600;text-transform:uppercase">Plan &amp; Pricing</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"left","style":{"elements":{"link":{"color":{"text":"#8c8c8c"}}},"color":{"text":"#8c8c8c"},"typography":{"lineHeight":"1.6"}}} -->
<p class="has-text-align-left has-text-color has-link-color" style="color:#8c8c8c;line-height:1.6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"2em","bottom":"2em","left":"2em"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:2em;padding-right:2em;padding-bottom:2em;padding-left:2em"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"32px"}}} -->
<h3 class="wp-block-heading" style="font-size:32px;font-style:normal;font-weight:700">Personal</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"}}} -->
<h2 class="wp-block-heading" style="font-size:30px;font-style:normal;font-weight:700">$49.99</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":4,"style":{"typography":{"fontStyle":"normal","fontWeight":"500"}},"fontSize":"medium"} -->
<h4 class="wp-block-heading has-medium-font-size" style="font-style:normal;font-weight:500">Featured Includes:</h4>
<!-- /wp:heading -->

<!-- wp:group {"style":{"spacing":{"blockGap":"10px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">Single Site Access</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">1 Year Free Support</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">1GB Hosting Free</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">Unmetered Bandwidth</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">1 Email Accounts</h5>
<!-- /wp:heading --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->

<!-- wp:buttons {"style":{"spacing":{"margin":{"top":"40px"}}}} -->
<div class="wp-block-buttons" style="margin-top:40px"><!-- wp:button {"textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"typography":{"fontStyle":"normal","fontWeight":"600","textTransform":"uppercase"},"border":{"radius":"3px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"fontSize":"small"} -->
<div class="wp-block-button has-custom-font-size has-small-font-size" style="font-style:normal;font-weight:600;text-transform:uppercase"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color wp-element-button" style="border-radius:3px">Get this Package</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"2em","bottom":"2em","left":"2em"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:2em;padding-right:2em;padding-bottom:2em;padding-left:2em"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"32px"}}} -->
<h3 class="wp-block-heading" style="font-size:32px;font-style:normal;font-weight:700">Agency</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#666565"}}},"color":{"text":"#666565"},"typography":{"fontStyle":"normal","fontWeight":"300","lineHeight":"1.5"}}} -->
<p class="has-text-color has-link-color" style="color:#666565;font-style:normal;font-weight:300;line-height:1.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"style":{"typography":{"fontStyle":"normal","fontWeight":"700","fontSize":"30px"}}} -->
<h2 class="wp-block-heading" style="font-size:30px;font-style:normal;font-weight:700">$249.99</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":4,"style":{"typography":{"fontStyle":"normal","fontWeight":"500"}},"fontSize":"medium"} -->
<h4 class="wp-block-heading has-medium-font-size" style="font-style:normal;font-weight:500">Featured Includes:</h4>
<!-- /wp:heading -->

<!-- wp:group {"style":{"spacing":{"blockGap":"10px"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">Single Site Access</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">1 Year Free Support</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">Unlimited Hosting Free</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">Unmetered Bandwidth</h5>
<!-- /wp:heading --></div>
<!-- /wp:group -->

<!-- wp:group {"style":{"spacing":{"blockGap":"15px"}},"layout":{"type":"flex","flexWrap":"nowrap"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"auto","height":"20px","sizeSlug":"full","linkDestination":"none","style":{"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvam9iNjgwLTAzMS14LWwxZGJ1amlmLmpwZw.jpg" alt="" style="width:auto;height:20px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":5,"style":{"typography":{"fontStyle":"normal","fontWeight":"400","fontSize":"16px","textTransform":"none"}}} -->
<h5 class="wp-block-heading" style="font-size:16px;font-style:normal;font-weight:400;text-transform:none">100+ Email Accounts</h5>
<!-- /wp:heading --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->

<!-- wp:buttons {"style":{"spacing":{"margin":{"top":"40px"}}}} -->
<div class="wp-block-buttons" style="margin-top:40px"><!-- wp:button {"textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"typography":{"fontStyle":"normal","fontWeight":"600","textTransform":"uppercase"},"border":{"radius":"3px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}}},"fontSize":"small"} -->
<div class="wp-block-button has-custom-font-size has-small-font-size" style="font-style:normal;font-weight:600;text-transform:uppercase"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color wp-element-button" style="border-radius:3px">Get this Package</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Service Block

## PURPOSE:

The purpose of this WordPress block pattern is to showcase the services offered by a business in an engaging, visual layout. It allows website visitors to quickly understand the key services and encourages them to learn more.

## DESCRIPTION:

The block pattern contains a "Services" section with a heading, brief introductory paragraph, and three columns displaying different services:

1. The first column highlights "StartUp Ideas" with an icon of a rocket and planets.

2. The second column features "Business Counseling" with an icon depicting graphs and charts.

3. The third column promotes "Digital Marketing" with an icon of a planet or globe.

Each service column includes a relevant image, heading, short description, and "Read More" button.

The section uses an appealing, consistent visual style with pale blue "Read More" buttons, gray descriptive text, and ample padding around the content.

## INSTRUCTIONS:

To recreate this block pattern in the WordPress editor:

1. Add a Group block and set it to full-width alignment. In the block settings, add 60px padding on all sides.

2. Inside the Group block, add another Group block with a max content width of 1180px.

3. Add a Heading block inside the nested Group, select Heading 3, and enter "Services". Set the font weight to 500.

4. Below the heading, add a Paragraph block with the intro text.

5. Add a Columns block with 3 columns and set 40px top margin. Set the block gaps to 2.5rem.

6. In each column, add an Image block and upload the relevant service image.

7. Below each image, add a Heading block, select Heading 4, enter the service name, and set 24px font size and 500 font weight.

8. Add a Paragraph below each heading with the service description. Set the text color to #545454.

9. In each column, add a Buttons block with a single button. Set the button background color to "pale-cyan-blue", border radius to 6px, and padding of 0.6rem top/bottom and 40px left/right. Enter "Read More" for the button text.

10. Double-check the layout matches the provided image and make any small styling adjustments as needed.

## Block Pattern

```
<!-- wp:group {"align":"full","style":{"spacing":{"padding":{"top":"var:preset|spacing|60","right":"var:preset|spacing|60","bottom":"var:preset|spacing|60","left":"var:preset|spacing|60"}}},"layout":{"type":"constrained","contentSize":"100%"}} -->
<div class="wp-block-group alignfull" style="padding-top:var(--wp--preset--spacing--60);padding-right:var(--wp--preset--spacing--60);padding-bottom:var(--wp--preset--spacing--60);padding-left:var(--wp--preset--spacing--60)"><!-- wp:group {"layout":{"type":"constrained","contentSize":"1180px"}} -->
<div class="wp-block-group"><!-- wp:heading {"level":3,"style":{"typography":{"fontStyle":"normal","fontWeight":"500"}}} -->
<h3 class="wp-block-heading" style="font-style:normal;font-weight:500">Services</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
<!-- /wp:paragraph -->

<!-- wp:columns {"style":{"spacing":{"margin":{"top":"var:preset|spacing|40"},"blockGap":{"top":"2.5rem","left":"2.5rem"}}}} -->
<div class="wp-block-columns" style="margin-top:var(--wp--preset--spacing--40)"><!-- wp:column -->
<div class="wp-block-column"><!-- wp:image {"sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA0L2pvYjcyMS0yMjFhLXguanBn.jpg" alt="" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":4,"style":{"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"500"}}} -->
<h4 class="wp-block-heading" style="font-size:24px;font-style:normal;font-weight:500">StartUp Ideas</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#545454"}}} -->
<p class="has-text-color" style="color:#545454">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
<!-- /wp:paragraph -->

<!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button {"backgroundColor":"pale-cyan-blue","style":{"border":{"radius":"6px"},"spacing":{"padding":{"left":"var:preset|spacing|40","right":"var:preset|spacing|40","top":"0.6rem","bottom":"0.6rem"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-pale-cyan-blue-background-color has-background wp-element-button" style="border-radius:6px;padding-top:0.6rem;padding-right:var(--wp--preset--spacing--40);padding-bottom:0.6rem;padding-left:var(--wp--preset--spacing--40)">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"><!-- wp:image {"sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0xNjQtdi5qcGc.jpg" alt="" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":4,"style":{"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"500"}}} -->
<h4 class="wp-block-heading" style="font-size:24px;font-style:normal;font-weight:500">Business Counseling</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#545454"}}} -->
<p class="has-text-color" style="color:#545454">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
<!-- /wp:paragraph -->

<!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button {"backgroundColor":"pale-cyan-blue","style":{"border":{"radius":"6px"},"spacing":{"padding":{"left":"var:preset|spacing|40","right":"var:preset|spacing|40","top":"0.6rem","bottom":"0.6rem"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-pale-cyan-blue-background-color has-background wp-element-button" style="border-radius:6px;padding-top:0.6rem;padding-right:var(--wp--preset--spacing--40);padding-bottom:0.6rem;padding-left:var(--wp--preset--spacing--40)">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"><!-- wp:image {"sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA0L2pvYjY4Mi0xNzItbDF1N2xwZnMuanBn.jpg" alt="" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":4,"style":{"typography":{"fontSize":"24px","fontStyle":"normal","fontWeight":"500"}}} -->
<h4 class="wp-block-heading" style="font-size:24px;font-style:normal;font-weight:500">Digital Marketing</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"style":{"color":{"text":"#545454"}}} -->
<p class="has-text-color" style="color:#545454">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
<!-- /wp:paragraph -->

<!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button {"backgroundColor":"pale-cyan-blue","style":{"border":{"radius":"6px"},"spacing":{"padding":{"left":"var:preset|spacing|40","right":"var:preset|spacing|40","top":"0.6rem","bottom":"0.6rem"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-pale-cyan-blue-background-color has-background wp-element-button" style="border-radius:6px;padding-top:0.6rem;padding-right:var(--wp--preset--spacing--40);padding-bottom:0.6rem;padding-left:var(--wp--preset--spacing--40)">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group --></div>
<!-- /wp:group -->
```

======

# Services Box

## PURPOSE:

The purpose of this layout is to showcase the key services offered by a business or organization in an appealing, organized way on their website. It provides a clear overview of the main service areas to inform visitors about the company's offerings.

## DESCRIPTION:

The layout contains a title "Our Services" with a short introductory paragraph below it. Underneath, there are three equal-width columns representing different services:

1. Digital Marketing
2. UI/UX Design
3. App Development

Each service column contains:

- A circular icon or image representing the service
- The service name as a heading
- A short description paragraph about the service
- A "Read More" button linking to more details

The service columns have a 1px gray border and consistent inner padding. The "Read More" buttons have rounded corners and a blue-to-purple gradient background.

## INSTRUCTIONS:

To recreate this services layout using the provided block pattern code:

1. Add a Columns block and set the top/bottom padding to 40px/20px. Inside the column, add a centered Heading block with the text "Our Services" and set its font size to 44px. Below that, add a centered Paragraph block with the intro text.

2. Below the intro, add another Columns block with 3 equal columns inside. Set the top/bottom margins to 25px/0 and left/right gap to 20px.

3. Inside each of the 3 columns:

   - Add an Image block, center-align it, set width to 50px
   - Add a centered Heading block with the service name, set font size to 24px and top margin to 32px
   - Add a centered Paragraph block with the service description
   - Add a center-justified Buttons block with top margin 32px, and inside it add a filled Button block with rounded corners, 10px top/bottom padding, white text, and a blue-to-purple gradient background

4. Set the border width to 1px and border color to cyan-bluish-gray for each of the 3 service columns. Set the text and link color to black (#000000).

5. Add consistent padding of 2em (32px) to the top, right, bottom, left of each service column. Adjust the right/left padding in the last column to 1.73em to account for the longer heading.

## Block Pattern

```
<!-- wp:columns {"style":{"spacing":{"padding":{"top":"40px","bottom":"20px"}}}} -->
<div class="wp-block-columns" style="padding-top:40px;padding-bottom:20px"><!-- wp:column {"style":{"spacing":{"blockGap":"14px"}}} -->
<div class="wp-block-column"><!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"44px","fontStyle":"normal","fontWeight":"600"}}} -->
<h2 class="wp-block-heading has-text-align-center" style="font-size:44px;font-style:normal;font-weight:600">Our Services</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#8b8b8b"}}},"color":{"text":"#8b8b8b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#8b8b8b">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"top":"25px","bottom":"0"},"blockGap":{"left":"20px"}}}} -->
<div class="wp-block-columns alignwide" style="margin-top:25px;margin-bottom:0"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"2em","bottom":"2em","left":"2em"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-text-color has-link-color" style="border-width:1px;color:#000000;padding-top:2em;padding-right:2em;padding-bottom:2em;padding-left:2em"><!-- wp:image {"align":"center","width":"50px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvam9iNjg0LTIyNC12LmpwZw.jpg" alt="" style="width:50px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"24px"},"spacing":{"margin":{"top":"32px"}}}} -->
<h2 class="wp-block-heading has-text-align-center" style="margin-top:32px;font-size:24px">Digital Marketing</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#777676"}}},"color":{"text":"#777676"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#777676">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"center"},"style":{"spacing":{"margin":{"top":"32px"}}}} -->
<div class="wp-block-buttons" style="margin-top:32px"><!-- wp:button {"textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"border":{"radius":"5px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"10px","bottom":"10px"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color wp-element-button" style="border-radius:5px;padding-top:10px;padding-bottom:10px">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"2em","bottom":"2em","left":"2em"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-text-color has-link-color" style="border-width:1px;color:#000000;padding-top:2em;padding-right:2em;padding-bottom:2em;padding-left:2em"><!-- wp:image {"align":"center","width":"50px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvam9iNjg0LTIyNC12LmpwZw.jpg" alt="" style="width:50px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"24px"},"spacing":{"margin":{"top":"32px"}}}} -->
<h2 class="wp-block-heading has-text-align-center" style="margin-top:32px;font-size:24px">UI/UX Design</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#777676"}}},"color":{"text":"#777676"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#777676">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"center"},"style":{"spacing":{"margin":{"top":"32px"}}}} -->
<div class="wp-block-buttons" style="margin-top:32px"><!-- wp:button {"textAlign":"center","textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"border":{"radius":"5px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"10px","bottom":"10px"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color has-text-align-center wp-element-button" style="border-radius:5px;padding-top:10px;padding-bottom:10px">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"2em","right":"1.73em","bottom":"2em","left":"1.73em"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-text-color has-link-color" style="border-width:1px;color:#000000;padding-top:2em;padding-right:1.73em;padding-bottom:2em;padding-left:1.73em"><!-- wp:image {"align":"center","width":"50px","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image aligncenter size-full is-resized"><img src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvam9iNjg0LTIyNC12LmpwZw.jpg" alt="" style="width:50px" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"24px"},"spacing":{"margin":{"top":"32px"}}}} -->
<h2 class="wp-block-heading has-text-align-center" style="margin-top:32px;font-size:24px">App Development</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#777676"}}},"color":{"text":"#777676"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#777676">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:buttons {"layout":{"type":"flex","justifyContent":"center"},"style":{"spacing":{"margin":{"top":"32px"}}}} -->
<div class="wp-block-buttons" style="margin-top:32px"><!-- wp:button {"textColor":"white","gradient":"vivid-cyan-blue-to-vivid-purple","style":{"border":{"radius":"5px"},"elements":{"link":{"color":{"text":"var:preset|color|white"}}},"spacing":{"padding":{"top":"10px","bottom":"10px"}}}} -->
<div class="wp-block-button"><a class="wp-block-button__link has-white-color has-vivid-cyan-blue-to-vivid-purple-gradient-background has-text-color has-background has-link-color wp-element-button" style="border-radius:5px;padding-top:10px;padding-bottom:10px">Read More</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Team Section

## PURPOSE:

The purpose of the "Meet Our Team" layout is to introduce key team members of an organization in an engaging and visually appealing way on a webpage.

## DESCRIPTION:

The layout features a title "Meet Our Team" with centered subtext. Below are three columns, each containing a team member's photo, name, title, and social media links. The photos are in a 3:4 aspect ratio and the backgrounds are white. The names use a 20px font size and the titles are in a smaller 14px gray font. Social media icons for Behance, Twitter, and LinkedIn are included under each person.

The three team members shown are:

- Matt Rally, CEO of Rally Industries
- Kaly Kom, CTO of Rally Industries
- Melinda M, UI/UX Designer at Rally Industries

## INSTRUCTIONS:

1. Insert a Group block and add 60px top padding. Inside, add a centered Heading block with 44px font size for the "Meet Our Team" title. Below that, add a centered Paragraph block in 16px gray font for the subtext.

2. Add a Columns block below with 3 columns and wide width. Add 50px top margin and 60px bottom padding to the columns.

3. In each column:

   - Insert an Image block, set to 3:4 aspect ratio, large size, and fill scaled
   - Add a centered Heading block for the name in 20px font with 25px top margin
   - Add a centered 14px gray Paragraph for the title
   - Insert a Social Links block with Behance, Twitter and LinkedIn icons, center aligned with 20px top margin and 6px gaps

4. Set the background color of each column to white and the text color to black.

5. For each team member's image, paste in the image URLs provided in the code for their photos.

6. Fill in each team member's name in the Heading blocks and their titles in the Paragraph blocks.

## Block Pattern

```
<!-- wp:group {"style":{"spacing":{"padding":{"top":"60px"}}},"layout":{"type":"constrained"}} -->
<div class="wp-block-group" style="padding-top:60px"><!-- wp:heading {"textAlign":"center","style":{"typography":{"fontSize":"44px","fontStyle":"normal","fontWeight":"600"}}} -->
<h2 class="wp-block-heading has-text-align-center" style="font-size:44px;font-style:normal;font-weight:600">Meet Our Team</h2>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#5b5c5d"}}},"color":{"text":"#5b5c5d"},"typography":{"fontSize":"16px","lineHeight":"1.5"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#5b5c5d;font-size:16px;line-height:1.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.&nbsp;</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"top":"50px","bottom":"0"},"padding":{"bottom":"60px"}}}} -->
<div class="wp-block-columns alignwide" style="margin-top:50px;margin-bottom:0;padding-bottom:60px"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:image {"aspectRatio":"3/4","scale":"cover","sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://c.pxhere.com/photos/37/8c/businessman_businessperson_man_male_portrait_indian_suit_elegant-947420.jpg!d" alt="" style="aspect-ratio:3/4;object-fit:cover" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"500"},"spacing":{"margin":{"top":"25px"}}}} -->
<h4 class="wp-block-heading has-text-align-center" style="margin-top:25px;font-size:20px;font-style:normal;font-weight:500">Matt Rally</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:14px">CEO, Rally Industries</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"6px"},"margin":{"top":"20px"}}},"layout":{"type":"flex","justifyContent":"center"}} -->
<ul class="wp-block-social-links" style="margin-top:20px"><!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /-->

<!-- wp:social-link {"url":"#","service":"linkedin"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:image {"aspectRatio":"3/4","scale":"cover","sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://c.pxhere.com/photos/49/af/girl_people_landscape_sun_tenderness_spring_light_vacation-750013.jpg!d" alt="" style="aspect-ratio:3/4;object-fit:cover" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"500"},"spacing":{"margin":{"top":"25px"}}}} -->
<h4 class="wp-block-heading has-text-align-center" style="margin-top:25px;font-size:20px;font-style:normal;font-weight:500">Kaly Kom</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:14px">CTO, Rally Industries</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"6px"},"margin":{"top":"20px"}}},"layout":{"type":"flex","justifyContent":"center"}} -->
<ul class="wp-block-social-links" style="margin-top:20px"><!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /-->

<!-- wp:social-link {"url":"#","service":"linkedin"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"0em","right":"0em","bottom":"0em","left":"0em"},"blockGap":"8px"}},"backgroundColor":"white"} -->
<div class="wp-block-column has-white-background-color has-text-color has-background has-link-color" style="color:#000000;padding-top:0em;padding-right:0em;padding-bottom:0em;padding-left:0em"><!-- wp:image {"aspectRatio":"3/4","scale":"cover","sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://c.pxhere.com/photos/75/ec/hair_salons_models_hair_color_trick_fashion_portrait_face-599108.jpg!d" alt="" style="aspect-ratio:3/4;object-fit:cover" /></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontSize":"20px","fontStyle":"normal","fontWeight":"500"},"spacing":{"margin":{"top":"25px"}}}} -->
<h4 class="wp-block-heading has-text-align-center" style="margin-top:25px;font-size:20px;font-style:normal;font-weight:500">Melinda M</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#59595b"}}},"color":{"text":"#59595b"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#59595b;font-size:14px">UI/UX Designer, Rally Industries</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"style":{"spacing":{"blockGap":{"left":"6px"},"margin":{"top":"20px"}}},"layout":{"type":"flex","justifyContent":"center"}} -->
<ul class="wp-block-social-links" style="margin-top:20px"><!-- wp:social-link {"url":"#","service":"behance"} /-->

<!-- wp:social-link {"url":"#","service":"twitter"} /-->

<!-- wp:social-link {"url":"#","service":"linkedin"} /--></ul>
<!-- /wp:social-links --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======

# Testimonials

## PURPOSE:

The purpose of this WordPress block layout is to showcase client testimonials on a website. It aims to build trust and credibility by featuring positive reviews from satisfied customers, along with their photos and titles.

## DESCRIPTION:

The layout consists of three columns, each containing a client testimonial. At the top, there is a centered heading that says "What Our Client Says".

Each testimonial column has a white background and a 1px border. The content includes:

- 5 star rating icons
- The testimonial text, centered and in a gray color
- A circular client photo, centered
- The client's name, centered and in bold
- The client's title/company, centered below their name

The columns are evenly spaced in a single row. The layout is designed to be visually appealing and easy to read, with a clean and professional look that puts the focus on the testimonials.

## INSTRUCTIONS:

1. Create a Columns block and set it to have 3 columns. Apply the "alignwide" class and adjust the margins and padding.

2. In each column:
   a. Add a border, set the background to white, and adjust the text color and padding.
   b. Add a Group block and inside it, insert 5 star icon images. Set them to 20px width, 1:1 aspect ratio, and center-align the group.
   c. Add a Paragraph block below the stars, paste in the testimonial text, and style it with gray text color, center alignment, and top/bottom margins.
   d. Below the testimonial, insert the client's image, set it to 80px width, 1:1 aspect ratio, and apply a circular border radius. Center-align the image.
   e. Add a Group block below the image for the client's name and title.
   f. Inside the group, add a centered Heading block for the name, and style it as bold 18px.
   g. Still inside the group, add a centered Paragraph block below the name for their title, and style it with 14px gray text.

3. Repeat step 2 for the remaining columns, replacing the text and images.

4. Above the columns, insert a centered Heading block for the section title "What Our Client Says", and style it as 600 weight, large size.

5. Adjust any spacing or styling as needed to match the provided image.

## Block Pattern

```
<!-- wp:heading {"textAlign":"center","style":{"typography":{"fontStyle":"normal","fontWeight":"600"},"spacing":{"margin":{"top":"60px"}}},"fontSize":"large"} -->
<h2 class="wp-block-heading has-text-align-center has-large-font-size" style="margin-top:60px;font-style:normal;font-weight:600">What Our Client Says</h2>
<!-- /wp:heading -->

<!-- wp:columns {"align":"wide","style":{"spacing":{"margin":{"bottom":"0"},"padding":{"top":"var:preset|spacing|30","bottom":"var:preset|spacing|50"}}}} -->
<div class="wp-block-columns alignwide" style="margin-bottom:0;padding-top:var(--wp--preset--spacing--30);padding-bottom:var(--wp--preset--spacing--50)"><!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"30px","right":"30px","bottom":"30px","left":"30px"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:30px;padding-right:30px;padding-bottom:30px;padding-left:30px"><!-- wp:group {"style":{"spacing":{"blockGap":"0"}},"layout":{"type":"flex","flexWrap":"nowrap","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image --></div>
<!-- /wp:group -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#6d6d6d"}}},"color":{"text":"#6d6d6d"},"spacing":{"margin":{"top":"30px","bottom":"40px"}}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#6d6d6d;margin-top:30px;margin-bottom:40px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"align":"center","width":"80px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none","style":{"border":{"radius":"50px"}}} -->
<figure class="wp-block-image aligncenter size-full is-resized has-custom-border"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA0L2ZsMTU0MDgzNzI5MjgtaW1hZ2Uta3B2emRtemEuanBn.jpg" alt="" style="border-radius:50px;aspect-ratio:1;object-fit:cover;width:80px" /></figure>
<!-- /wp:image -->

<!-- wp:group {"style":{"spacing":{"blockGap":"4px"}},"layout":{"type":"flex","orientation":"vertical","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"18px"}}} -->
<h4 class="wp-block-heading has-text-align-center" style="font-size:18px;font-style:normal;font-weight:600">Matt Leo</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#8f9194"}}},"color":{"text":"#8f9194"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#8f9194;font-size:14px">Manager, Matt Industry</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"30px","right":"30px","bottom":"30px","left":"30px"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:30px;padding-right:30px;padding-bottom:30px;padding-left:30px"><!-- wp:group {"style":{"spacing":{"blockGap":"0"}},"layout":{"type":"flex","flexWrap":"nowrap","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image --></div>
<!-- /wp:group -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#6d6d6d"}}},"color":{"text":"#6d6d6d"},"spacing":{"margin":{"top":"30px","bottom":"40px"}}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#6d6d6d;margin-top:30px;margin-bottom:40px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"align":"center","width":"80px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none","style":{"border":{"radius":"50px"},"color":{"duotone":"unset"}}} -->
<figure class="wp-block-image aligncenter size-full is-resized has-custom-border"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA0L2ZsMTU0MDgzNzI5MjgtaW1hZ2Uta3B2emRtemEuanBn.jpg" alt="" style="border-radius:50px;aspect-ratio:1;object-fit:cover;width:80px" /></figure>
<!-- /wp:image -->

<!-- wp:group {"style":{"spacing":{"blockGap":"4px"}},"layout":{"type":"flex","orientation":"vertical","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"18px"}}} -->
<h4 class="wp-block-heading has-text-align-center" style="font-size:18px;font-style:normal;font-weight:600">Henry M</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#8f9194"}}},"color":{"text":"#8f9194"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#8f9194;font-size:14px">CEO, Henry Tech</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"style":{"color":{"text":"#000000"},"elements":{"link":{"color":{"text":"#000000"}}},"spacing":{"padding":{"top":"30px","right":"30px","bottom":"30px","left":"30px"}},"border":{"width":"1px"}},"borderColor":"cyan-bluish-gray","backgroundColor":"white"} -->
<div class="wp-block-column has-border-color has-cyan-bluish-gray-border-color has-white-background-color has-text-color has-background has-link-color" style="border-width:1px;color:#000000;padding-top:30px;padding-right:30px;padding-bottom:30px;padding-left:30px"><!-- wp:group {"style":{"spacing":{"blockGap":"0"}},"layout":{"type":"flex","flexWrap":"nowrap","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image -->

<!-- wp:image {"width":"20px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full is-resized"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L2pvYjcyOC0wOTEtcC5wbmc.png" alt="" style="aspect-ratio:1;object-fit:cover;width:20px" /></figure>
<!-- /wp:image --></div>
<!-- /wp:group -->

<!-- wp:paragraph {"align":"center","style":{"elements":{"link":{"color":{"text":"#6d6d6d"}}},"color":{"text":"#6d6d6d"},"spacing":{"margin":{"top":"30px","bottom":"40px"}}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#6d6d6d;margin-top:30px;margin-bottom:40px">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"align":"center","width":"80px","aspectRatio":"1","scale":"cover","sizeSlug":"full","linkDestination":"none","style":{"border":{"radius":"50px"}}} -->
<figure class="wp-block-image aligncenter size-full is-resized has-custom-border"><img src="https://images.rawpixel.com/image_1300/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA0L2ZsMTU0MDgzNzI5MjgtaW1hZ2Uta3B2emRtemEuanBn.jpg" alt="" style="border-radius:50px;aspect-ratio:1;object-fit:cover;width:80px" /></figure>
<!-- /wp:image -->

<!-- wp:group {"style":{"spacing":{"blockGap":"4px"}},"layout":{"type":"flex","orientation":"vertical","justifyContent":"center"}} -->
<div class="wp-block-group"><!-- wp:heading {"textAlign":"center","level":4,"style":{"typography":{"fontStyle":"normal","fontWeight":"600","fontSize":"18px"}}} -->
<h4 class="wp-block-heading has-text-align-center" style="font-size:18px;font-style:normal;font-weight:600">Marcus Y</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":"14px"},"elements":{"link":{"color":{"text":"#8f9194"}}},"color":{"text":"#8f9194"}}} -->
<p class="has-text-align-center has-text-color has-link-color" style="color:#8f9194;font-size:14px">Product Manager, Y Industry</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->
```

======
