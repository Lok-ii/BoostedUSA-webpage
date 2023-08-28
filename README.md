# BoostedUSA-webpage


Hosted Link:- https://lok-ii.github.io/BoostedUSA-webpage/



![Screenshot 2023-08-28 141214](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/eeb8876d-1d07-4c06-a6a0-a6c54024c105)

		<header>: This is the header section of the webpage. It typically contains navigation menus, logos, and other key elements.

		<nav class="primary">: This represents the primary navigation section of the header, where the main navigation elements are placed.
		
		<img>: This is an image element containing the website's logo. The src attribute specifies the image file's path, and the alt attribute provides alternative text for accessibility.
		
		<div class="nav-links">: This is a container for navigation links and user-related links.
		
		<ul class="links">: This is an unordered list containing navigation links. Each <li> represents a single navigation item.
		
		<ul class="user">: This is an unordered list containing user-related links. The list items contain icons using the Font Awesome icon classes.
		
		<nav class="secondary">: This represents the secondary navigation section of the header, typically used for smaller screens or mobile devices.
		
		<i class="fa-solid fa-bars"></i>: This is an icon representing a menu bar, often used to indicate a menu toggle for mobile navigation.
		
		<img>: Another logo image, similar to the primary navigation logo.
		
		<ul>: An unordered list containing icons, potentially representing actions like search and shopping cart.

  	CSS : 

   		header: This rule sets the styling for the entire header section. It has a fixed height of 4rem, spans the full width of the viewport, has a background color of #eaebed, and is positioned as sticky at the top of the viewport.
		
		.secondary: This class is used to hide the secondary navigation on larger screens. The display: none; property hides the element.
		
		.primary: This class is applied to the primary navigation container. It's a flex container that aligns its items vertically and justifies them with space between. It has a background color of #f7f7f7.
		
		.primary img: Styles the primary navigation logo. It has a maximum width of 12.5rem, a pointer cursor on hover, and a smooth opacity transition.
		
		.primary img:hover: This rule changes the logo's opacity on hover and adds a smooth transform effect.
		
		.nav-links: This class styles the container for navigation links. It's a flex container with space between items, aligning them vertically.
		
		.links, .user: Styles the navigation link lists and user-related link list. They're displayed as flex containers with no list-style, a font size of 0.9rem, and a letter spacing effect.
		
		.links li:hover, .user li:hover: These rules define the color change on hover for navigation links and user links.
		
		.user: Adds a smaller gap between user-related links.


![Screenshot 2023-08-28 141230](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/1ef1dd13-3169-4618-9b11-c207c593c95c)
![Screenshot 2023-08-28 141246](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/cd6d2421-7c9a-495c-969d-b8361a2e5207)


		This is section with the class home, which encompasses several image containers representing different brands of products. Each brand's image is enclosed within a div with the class outer-image-container. Inside this container, there's another div with a class specific to each brand (e.g., boostedusa, super73, etc.), and within that, there's a div with the class transparent-bg containing an image (img), a line break (<br>), and a paragraph (<p>) of text.

  	CSS:-
		
		The .home class styles the overall section. It sets the width and height, and configures the section as a grid with two equal columns. The grid-template-areas property is used to specify the areas where the contents will be placed within the grid.
		The .outer-image-container class hides any overflow of content within it. This is useful to ensure that the content doesn't spill out of its designated area.
		The .back-image class styles the background images of each brand's container. It sets the width and height to 100%, applies a transition effect for smoother scaling, centers the background image, and adjusts its size to cover the container while preventing repetition.
		The .outer-image-container:hover .back-image rule scales up the background image container within .outer-image-container when hovering over it. The transform property with scale enlarges the image by a factor of 1.1 (10% larger), creating a zoom effect. The transition property ensures that the scaling change is smooth.
		The .transparent-bg class creates a translucent background for the content of each brand's container. It centers the content both horizontally and vertically using flexbox properties. The background-color property sets the background to a semi-transparent white color.
		Each brand-specific class (e.g., .boostedusa, .super73, etc.) sets the background image URL for that specific brand's container.


  ![Screenshot 2023-08-28 141254](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/aa5c91ef-5d76-46c2-90da-57e072618c1e)

  		<section class="logo-list">: This is a <section> element with a class of "logo-list". It's being used to group and style the logo images together. The class name "logo-list" is likely used for applying specific styles to this section.

		<img class="logos" src="..." alt="...">: These are four <img> elements with a class of "logos". Each <img> element represents a logo image with its own src (source) attribute pointing to the image file and an alt attribute providing alternative text for accessibility. The "logos" class might be used for applying styles to these images.
		
		The src attributes contain paths to different image files. The src attribute specifies the image source location.
		The alt attributes provide alternative text that is displayed if the image can't be loaded or for accessibility purposes.
		
  
  	To summarize, this HTML code creates a section containing four logo images. The images are represented using the <img> element, each with its own source (src) and alternative text (alt). The class names "logo-list" and "logos" are likely used for applying CSS styles to the section and the images respectively.


   	CSS:-

	 	The .logo-list class is used to style the surrounding container, which holds the logos. The styles applied to it include:

			width: 100%;: This ensures the container spans the full width of its parent.
			background-color: var(--black);: This sets the background color of the container. It seems to be using a custom CSS variable --black for the color.
			display: flex;: This establishes a flex container, allowing the logos to be laid out in a flex layout.
			flex-wrap: wrap;: With this property, if the logos exceed the width of the container, they will wrap to the next line.
			align-items: center;: This centers the items vertically within the container.
			justify-content: space-evenly;: This evenly distributes the logos horizontally with some space between them.
			height: 5rem;: This sets the height of the container to 5rem.
		
  		The .logos class is used to style the individual logo images. The styles applied are:
			
			max-width: 8rem;: This limits the maximum width of each logo to 8rem.
			max-height: 3rem;: This limits the maximum height of each logo to 3rem.


![Screenshot 2023-08-28 141305](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/2a36ff28-e55e-48a8-9325-0fd7c0104c75)
![Screenshot 2023-08-28 141316](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/4fd7c0bc-075b-43c2-8b3b-c9f34c620924)
![Screenshot 2023-08-28 141332](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/1c654b67-be44-42ee-a715-fa8ccc01d45f)
![Screenshot 2023-08-28 141341](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/e2ad2416-15b5-43e1-8766-0e217a13a2db)


		<section class="why-section">: This is the main section that wraps everything related to the "why-section." It's likely used for applying styles to this particular section of content.
		
		<div class="offers">: This division contains introductory content and offers related to the products. Inside this division, you have several headings and paragraphs providing information about the products being offered.
		
		<hr />: This is a horizontal rule (a line) that separates the introductory content from the product-specific content. It's a common way to visually divide different sections of content.
		
		<div class="why-super73">, <div class="why-minimotors">, <div class="why-evolve">: These divisions represent different sections for explaining why customers might be interested in Super73 electric bikes, Minimotors electric scooters, and Evolve skateboards. Each of these divisions contains an image container and a content container.
		
		Inside each of the product-specific divisions (why-super73, why-minimotors, and why-evolve), you have the following structure:
		
		An image container (image-container) that likely holds an image representing the respective product.
		A content container (content-container) that holds information and details about the product, including headings, paragraphs, and a button for shopping.
	
 	Overall, this HTML code creates a comprehensive "why-section" that introduces different products (Super73 bikes, Minimotors electric scooters, and Evolve skateboards) and provides information about each product's features, benefits, and reasons to consider them. It's structured using <section> and <div> elements for organizing content and applying specific styles.

  	CSS:-
   		.why-section: Styles the main section that wraps the "why-section" content.
			width: 100%: Makes sure the section spans the full width of its parent container.
			display: flex; flex-direction: column;: Sets the display mode to flex and arranges child elements vertically (column-wise).
			align-items: center;: Horizontally centers the content within the section.
			padding: 2rem 0;: Adds vertical padding of 2rem and no horizontal padding.
		
		.offers: Styles the introductory content with padding and centers the text.
		
		.why-super73 and .why-evolve: Styles the product sections using flex properties. These sections are displayed as flex containers with space evenly distributed between items and wrap to new lines if needed.
		
		.image-container: Styles the container for the product images. It sets a fixed width and height and hides any overflow.
		
		.inner-container: Styles the inner container of the images. It sets the background properties for the images, including position, size, and transition effects.
		
		.container73, .super73image, .minimotorsimage, .evolveimage: Styles for different images used in the sections, including their background images and dimensions.
		
		.inner-container:hover: Specifies a hover effect for the images, enlarging them slightly on hover.
		
		.content-container: Styles the container for the textual content of the product sections.
		
		.why-minimotors: Styles the section related to Minimotors with reversed row direction, aligning content to the right, and space evenly distributed between items.
		
		.paragraph: Styles the paragraph text with a specific line height.

![Screenshot 2023-08-28 141354](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/6ff6b59b-93eb-44ff-9869-2a7f7a3dca2f)

		<section class="electric-scooter">: This creates a section element with a class of "electric-scooter," likely for applying specific styles to this section.

		<h4>High-performance</h4>: This is a level 4 heading element that seems to emphasize the high performance of the electric scooters.
		
		<h1>Electric Scooters</h1>: This is a level 1 heading element, the largest heading, which introduces the main title of the section, "Electric Scooters."
		
		The following <h4> element contains a description of the benefits of using electric scooters. The <br /> tags are used to create line breaks in the text, providing a visually appealing layout.
		
		<button>Shop Now</button>: This button invites users to shop for electric scooters.

	CSS:-

		.electric-scooter: This is a class selector targeting the section with the class "electric-scooter."

			padding-top: 2rem;: This adds vertical spacing at the top of the section, giving it some breathing space.
		
			text-align: center;: This centers the text content within the section horizontally.
		
			width: 100%;: This ensures that the section spans the entire width of its containing element.
		
			min-height: 41.5rem;: This sets a minimum height for the section, ensuring that it takes up a certain amount of vertical space even if the content is minimal.
		
			background-image: url(./Assets/electric-scooter.webp);: This sets the background image of the section using the provided URL. The image is displayed as the background.
			
			background-position: center;: This positions the background image at the center of the section.
			
			background-size: cover;: This ensures that the background image covers the entire section, even if it needs to be scaled.
			
			background-repeat: no-repeat;: This prevents the background image from repeating.

  		.electric-scooter button: This targets the button element within the "electric-scooter" section.

			padding: 0.5rem 5rem;: This adds padding to the top and bottom of the button, as well as significant padding to the left and right, creating a wide button.

   		.electric-scooter h1: This targets the level 1 heading element within the "electric-scooter" section.

			font-size: 2.8rem;: This sets the font size of the heading to 2.8 rem (relative em units), making it larger and more prominent.
   		
	 	.electric-scooter h4: This targets the level 4 heading element within the "electric-scooter" section.

			font-size: 0.9375rem;: This sets the font size of the heading to 0.9375 rem, making it relatively smaller.
			
			letter-spacing: 0.08rem;: This adds a slight letter spacing to the heading text for better readability.


![Screenshot 2023-08-28 141834](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/d3eabd68-4236-4e1e-99c0-d3d34cd43ce6)

		<section class="youtube">: This is a section element with the class attribute "youtube." It's used to create a section on the webpage that will contain the embedded YouTube video.

		<iframe>: This is an iframe (inline frame) element, which is used to embed external content, such as videos, within a webpage.
		
			src="https://www.youtube.com/embed/1eLZBg9Qdbw?si=BVkf4jnvMQHWUU8U": The src attribute specifies the source URL of the YouTube video to be embedded. The URL points to the YouTube video with the unique identifier "1eLZBg9Qdbw" and includes a query parameter "si=BVkf4jnvMQHWUU8U."
   			allowfullscreen: The allowfullscreen attribute allows the iframe to be displayed in full-screen mode.

   	Overall, this HTML code creates a section on the webpage that contains an embedded YouTube video. The video is loaded from the specified source URL and is displayed within an iframe element. The allow attribute specifies the permissions granted to the embedded content. The section itself is given the class "youtube," which could be used for styling or JavaScript interactions.

 	CSS:-
  		.youtube: This CSS class selector targets the section with the class "youtube," which contains the embedded YouTube video.

			width: 100%: This rule sets the width of the section to 100% of its containing element, ensuring it spans the entire available width.
			max-width: 1180px: This rule sets a maximum width of 1180 pixels for the section. This helps to limit the width on larger screens and prevents the content from becoming too stretched.
			height: 41.5rem;: This rule sets the height of the section to 41.5 rem (1 rem is equivalent to the font size of the root element, usually the <html> element). This defines the vertical space occupied by the section on the webpage.
			padding: 2rem 0.625rem 2rem 0.625rem;: This rule sets the padding of the section. Padding adds space around the content within the section. The values are applied in the following order: top, right, bottom, left. In this case, there's vertical padding of 2 rem and horizontal padding of 0.625 rem (about 10 pixels).

		.youtube iframe: This CSS selector targets the <iframe> element that's contained within the section with the class "youtube."

			width: 100%: This rule sets the width of the embedded <iframe> to 100% of its containing element, which in this case is the .youtube section. This ensures that the iframe spans the entire width available within the section.
			height: 100%: This rule sets the height of the embedded <iframe> to 100% of its containing element. This ensures that the iframe's height matches the height of the .youtube section, effectively filling the entire vertical space of the section.

![Screenshot 2023-08-28 141848](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/00026214-24ed-47b2-b18c-e135297e2f7d)


		HTML:
			<section class="skateboard">: This is a <section> element with the class "skateboard." It represents a section of content on the webpage.			
			<h4>All Terrain + Street</h4>: This <h4> element contains the text "All Terrain + Street." It represents a subheading for the section.			
			<h1>The Best All Terrain <br /> Skateboard!</h1>: This <h1> element contains the main heading text "The Best All Terrain Skateboard!" with a line break (<br />) to create a new line for "Skateboard!" It represents the main title of the section.
   			<h4>2-In-1</h4>: This <h4> element contains the text "2-In-1." It represents another subheading for the section.			
			<button>Shop Now</button>: This <button> element represents a call-to-action button for shopping. It will likely be used to navigate to a shopping page or perform a related action.

	CSS:

		.skateboard: This class selector targets the section with the class "skateboard." It contains styles for the entire section.
		
			text-align: center;: This rule centers the text content within the section horizontally.			
			padding: 4rem 0;: This rule adds padding of 4 rems (a unit of measurement) at the top and bottom of the section, providing space around the content.			
			width: 100%;: This rule sets the width of the section to 100% of its containing element, ensuring it spans the entire available width.			
			background-color: var(--black);: This rule sets the background color of the section to a variable named "--black" (likely defined elsewhere in the CSS).			
			color: var(--white);: This rule sets the text color within the section to a variable named "--white" (likely defined elsewhere in the CSS).

		.skateboard h1: This selector targets the <h1> element within the "skateboard" section.
  
			font-size: 2.5rem;: This rule sets the font size of the <h1> element to 2.5 rems.			
			line-height: 1.4;: This rule sets the line height of the <h1> element to 1.4, providing some spacing between lines of text.

		.skateboard h4: This selector targets the <h4> elements within the "skateboard" section.
		
			font-size: 1rem;: This rule sets the font size of the <h4> elements to 1 rem.			
			letter-spacing: 0.08rem;: This rule adds a small amount of letter spacing to the <h4> elements.			
			.skateboard button: This selector targets the <button> element within the "skateboard" section.			
			padding: 0.5rem 2.5rem;: This rule sets the padding of the button, adding 0.5 rems of padding at the top and bottom and 2.5 rems of padding on the left and right.

![Screenshot 2023-08-28 141900](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/5731fd8b-ad10-435d-8479-712854371ad0)
![Screenshot 2023-08-28 141906](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/2c7c64ba-302d-43c6-bc12-2454f95c7f30)
![Screenshot 2023-08-28 141913](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/bba5731d-1ad0-4f4f-95c1-1bcf167dfd29)

  		Section: boosted-accessories
			.boosted-accessories: This class selector targets the section with the class "boosted-accessories" and is intended to apply styles to the entire section.
			.item-container: This class selector targets the container that holds each individual item.			
			.item: This class selector targets each individual item within the container.

		Section: evolve-accessories
  			.evolve-accessories: This class selector targets the section with the class "evolve-accessories" and applies styles to the entire section.
			.item-container: This class selector targets the container that holds each individual item.			
			.item: This class selector targets each individual item within the container.

  		Section: minimotors-accessories
			.minimotors-accessories: This class selector targets the section with the class "minimotors-accessories" and applies styles to the entire section.
			.item-container: This class selector targets the container that holds each individual item.			
			.item: This class selector targets each individual item within the container.

	CSS:-

 		.boosted-accessories, .evolve-accessories, .minimotors-accessories: These class selectors target the sections with the respective class names and apply similar styling rules to all of them.

		.item-container: This class selector targets the container that holds the individual accessory items. It has the following styling properties:
		
			width: 100%: The container occupies the full width of its parent.
			display: flex: The items are displayed in a flex container.
			flex-direction: column: The items are stacked vertically.
			justify-items: center: Items are centered horizontally.
			align-items: center: Items are centered vertically.
			padding: 3rem 0: Padding is added to the top and bottom of the container.

		.item-container::-webkit-scrollbar: This pseudo-element selector targets the scrollbar within the .item-container and hides it using display: none.

		.item: This class selector targets each individual accessory item within the container. It has the following styling properties:

			display: flex: The item content is displayed as a flex container.
			flex-direction: column: The content is stacked vertically.
			align-items: center: Content is centered vertically.
			justify-items: center: Content is centered horizontally.
		
  		.item img: This selector targets the images within each accessory item. It applies styling to the images, such as setting their width and height and preventing them from being selectable.

![Screenshot 2023-08-28 141921](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/07e74f0e-61bd-40aa-be4d-b2095b66bfd8)

	This is a section for subscribing to a newsletter. Here's a breakdown of the elements and their purpose:
		
		<section class="newsletter">: This creates a section with the class "newsletter" to contain the newsletter subscription content.		
		<h1>Subscribe to our Newsletter</h1>: A heading that indicates the purpose of the section.		
		<p>Sign up to get the latest on sales, new releases and more …</p>: A paragraph providing a brief description of what users can expect by subscribing.		
		<label class="email" for="email"><span>* </span>Email</label>: A label for the email input field, with an asterisk indicating it's a required field.		
		<input type="email" name="Email" id="email" required autocomplete="email"/>: An email input field where users can enter their email address. It has the attributes "required" to enforce that the field must be filled and "autocomplete" to suggest email addresses.		
		<p class="marketing">...</p>: A paragraph explaining the terms of subscribing and the information users can expect to receive. It also includes a link to Constant Contact, the email service provider.	
		<button class="sign-in" type="submit">Sign up!</button>: A button that users can click to submit their subscription. It has the class "sign-in" and is of type "submit."		
		<button class="contact-button">...</button>: A button that likely links to additional contact information. It contains an image with the source pointing to "./Assets/constant-contact.svg."

	This HTML structure creates a visually pleasing and informative section for users to subscribe to the newsletter.

	CSS:-

 		.newsletter: This selector styles the entire newsletter section. It sets the width to 100%, gives it a light gray background color (#e5e5e5), arranges its contents in a column, centers the content horizontally and vertically, and adds padding around the content.
   		.newsletter .marketing and .marketing a: These selectors style the text within the paragraph containing marketing information and the links within it. They set the font size to 0.6875rem (approximately 11px) and the text color to black.
	 	.newsletter input: This selector styles the input field within the newsletter section. It sets the height, padding, border, border-radius, and removes the default outline.
   		.newsletter input:focus: This selector styles the input field when it receives focus. It changes the border color to a light blue (#5dacd6).
	 	.email: This selector styles the label for the email input field. It aligns the text to the left and sets the font weight to 600 (bold).
   		.email span: This selector styles the asterisk within the label. It sets the color to a custom variable --links-buttons, which likely represents a specific color defined elsewhere in the CSS or a stylesheet.
	 	.newsletter .sign-in: This selector styles the "Sign up!" button within the newsletter section. It adds a border-radius of 5px to round the button's corners.
   		.contact-button: This selector styles the button with the class "contact-button." It sets the background color using a custom variable --gray-background, removes the border, adds some top margin, and sets padding.
	 	.contact-button img: This selector styles the image within the "contact-button." It sets the width and height of the image.


  
![Screenshot 2023-08-28 141927](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/b50f3a93-2ff6-4fa3-837e-5f1ecbecd56a)

	This section defines a "Features" section with four different features displayed as individual elements inside it.

		.features-container: This is the container for the entire "Features" section. It likely has some CSS styles associated with it, which you haven't provided here.		
		.feature: This class is applied to each individual feature within the section. It contains an image, a heading (<h1>), and a paragraph (<p>) describing the feature.
  
		Each .feature contains the following structure:
		
		An <img> element that displays an image related to the feature. The src attribute specifies the path to the image file, and the alt attribute provides alternative text for accessibility.		
		An <h1> element that displays the title of the feature. For example, "Go Fast" or "Go Further."		
		A line break <br />.		
		A <p> element that contains a description of the feature. The text explains the unique aspects or benefits of the particular feature.
  
	This structure is repeated for each of the four features within the .features-container section. Each feature has its own image, title, and description that describe different aspects of the Boosted and Evolve products. This arrangement allows visitors to quickly understand the key features and benefits of the products being showcased.

	CSS:-

   		.features-container: This class styles the container for the "Features" section. The styles include:
			width: 100%: The container spans the full width of its parent.
			min-height: 22.1875rem: The minimum height of the container is set.
			height: auto: The height adjusts automatically based on content.
			background-color: var(--black): The background color is set using a CSS variable, likely defined elsewhere in the styles.
			color: var(--white): The text color is set using a CSS variable.
			display: flex: The container uses flexbox for layout.
			justify-content: space-evenly: Items are distributed with even spacing along the main axis.
			flex-wrap: wrap: Items wrap to the next row when there's not enough space.
			padding: 2rem 0: Adds vertical padding of 2rem and no horizontal padding.

   		.feature: This class styles each individual feature box within the "Features" section. The styles include:
			height: 90%: The feature boxes take up 90% of the height of the container, allowing space for the background.
			display: flex: The feature boxes use flex layout.
			flex-direction: column: Items inside each feature box are stacked vertically.
			align-items: center: Items are centered along the cross-axis (vertically).
			justify-content: center: Items are centered along the main axis (horizontally).
			text-align: center: The text within each feature box is centered.
			line-height: 1.4rem: Sets the line height for better text readability.

   		.feature img: This styles the images within each feature box.
			max-width: 5rem: Limits the maximum width of the image to 5rem.
			max-height: 5rem: Limits the maximum height of the image to 5rem.

![Screenshot 2023-08-28 141940](https://github.com/Lok-ii/BoostedUSA-webpage/assets/129180844/1ce02816-0221-43f6-892e-7db787d6c6bc)


		This section represents the footer section of a webpage. It contains three main divisions:

		.footer-content: This division contains the main content of the footer, including an image, navigation links, and about information.
		
			An image is displayed, presumably a Boosted Boards image.
			The .explore division contains a header with the text "Explore" and an unordered list with navigation links.
			The .about division contains a header with the text "About Boosted USA" and a paragraph describing Boosted's mission and address.
		
  		.terms: This division contains copyright and credit information.

	The footer text includes the copyright year, links to Boosted USA's Terms of Service.
	An image is displayed, possibly showing accepted payment methods.

 	CSS:- 

  		.footer: Sets the width of the footer to 100% of its containing element.
		.footer-content: Defines the styles for the main content area of the footer, including background color, alignment, spacing, and flex layout.
		.explore ul: Styles the unordered list within the "Explore" section, removing list bullet points and adjusting font size and line height.
		.explore ul a: Styles the links within the "Explore" section, removing underlines, changing text color, and adding a smooth transition effect on hover.
		.about: Sets the width of the "About" section to 25% of its containing element.
		.terms: Defines styles for the "Terms" section, adjusting the layout, padding, alignment, and flex layout.
		.terms p: Sets the font size for text within the "Terms" section.
		.terms a: Styles links within the "Terms" section, removing underlines.
 			
