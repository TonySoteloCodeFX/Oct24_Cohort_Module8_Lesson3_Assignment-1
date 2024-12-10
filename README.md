<h1>Module 8 Lesson 3: CSS Layout Design<h1>
<hr>

<h2>1. Mastering Responsive Design with CSS Flexbox</h2>

<b>Objective:</b> The aim of this assignment is to apply the principles of CSS Flexbox and responsive design to create a flexible and adaptive web page layout. Students will learn to use Flexbox properties to manage the layout for different screen sizes, enhancing the user experience across devices.

<b>Problem Statement:</b> In the age of mobile devices, creating web layouts that adjust and adapt to various screen sizes is crucial. Traditional CSS layout techniques often fall short of providing the flexibility and responsiveness needed. CSS Flexbox offers a powerful toolset for designing complex layouts that are both fluid and responsive. This assignment challenges you to leverage CSS Flexbox to build a layout that responds gracefully to different viewport sizes.

<h3>Task 1</h3>

Create a Basic Flexbox Layout Start by creating a simple webpage layout using Flexbox. Your layout should include a header, a navigation menu, a main content area, and a footer. Utilize flex-direction to make sure your navigation menu is reading horizontally and your main content is reading vertically. 

<b>Requirements for this task:</b>

- Navigation Menu should contain at least 3 things (i.e. Home, Profile, About) and be arranged horizontally on the top of the page
<br>

- Header section should contain a background image and header text
    - Header Text should be bold, contrast color and Centered
<br>

- Main Content should contain at least 2 different children divs with content and be arranged vertically stacked on top of one another
<br>

- Footer should contain at least 3 sections (i.e. Contact Us, Events, Blog) and be arranged horizontally 

<b>Expected Outcome:</b> A webpage with a basic Flexbox layout, displaying a header, navigation, main content, and footer in a columnar arrangement.

<h3>Task 2</h3>

Implement Responsive Design Modify your Flexbox layout to include responsive design elements. Use media queries to adjust the layout for smaller screens, converting the navigation and footer content areas into a column format when the viewport width is less than 600px.

<b>Expected Outcome:</b> The webpage layout adjusts for smaller screens, with the navigation and main content side by side, while the header and footer span the full width of the viewport.

<h3>Task 3</h3>

Enhance the Layout with Flexbox Properties Further enhance your layout by using Flexbox properties such as justify-content, align-items, and flex-grow. Adjust these properties to ensure that the main content area takes up the remaining space between the header and footer, and centers the content within the navigation and main content areas.

<b>Expected Outcome:</b> The main content area expands to fill the space between the header and footer. Content within the navigation and main areas is centered, providing a balanced and visually appealing layout.

<hr>

<h2>Building Responsive Layouts with CSS Grid</h2>

<b>Objective:</b> The aim of this assignment is to familiarize students with the CSS Grid layout system and its application in creating responsive web designs. By the end of this assignment, students should be able to utilize CSS Grid properties to construct and adapt web page layouts for different screen sizes.

<b>Problem Statement:</b> Creating web layouts that are both aesthetically pleasing and functional across a variety of devices is a key challenge in modern web design. CSS Grid offers a powerful and flexible approach to designing web page layouts that can dynamically adjust to screen size, enhancing the user experience. This assignment challenges you to apply CSS Grid techniques to design a responsive web layout that gracefully transitions across different viewing devices.

<h3>Task 1</h3>

Create a Basic CSS Grid Layout Start by designing a simple web page layout using CSS Grid. Your layout should include a header, a main content area divided into two columns (for content and sidebar), and a footer. Define the grid container and set up the grid template areas.

<b>Expected Outcome:</b> A web page with a CSS Grid-based layout, featuring a header, a two-column main content area, and a footer.

<h3>Task 2</h3>

Implement Responsive Design Using CSS Grid Modify your CSS Grid layout to be responsive. Use media queries to change the layout for smaller screens by stacking the content and sidebar vertically instead of horizontally.

<b>Expected Outcome:</b> The layout changes to a single-column format on screens narrower than 768 pixels, stacking the header, content, sidebar, and footer vertically.

<h3>Task 3</h3>

Advanced Grid Layout with Template Columns and Rows Enhance your grid layout by specifying the size of columns and rows using the grid-template-columns and grid-template-rows properties. Experiment with fractional units (fr) and fixed sizes (e.g., pixels) to create a balanced layout.

<b>Expected Outcome:</b> A more refined layout where the main content area is larger than the sidebar on wider screens, with responsive adjustments for smaller devices.