# [SDF09] Responsive Footer Design with Tailwind CSS

Create a responsive footer for a website using Tailwind CSS. This project aims to enhance your CSS skills, focusing on responsive design and the utility-first approach of Tailwind CSS.

![alt text](Footer.png)

## Objectives
- Clone the provided starter code.
- Style the footer using Tailwind CSS.
- Apply Tailwind CSS to design a responsive footer.
- Learn to use Tailwind's grid system for layout design.
- Design a newsletter subscription section, a quick links section, and optionally add social media links.
- Test your footer's responsiveness.
- Submit your GitHub repository link via the LMS.

## Deliverables
Submit a GitHub link containing your project files, showcasing the completed responsive footer.

## Detailed Steps
1. **Grid Layout Setup**: Utilize Tailwind's grid system to create a responsive layout for your footer sections.
2. **Style Subscription Section**: Design a visually appealing subscription area with an input field and a button.
3. **Quick Links and Technologies**: Organize these sections for easy navigation.
4. **Add Social Media Links**: (Optional) Include social media icons, ensuring they're responsive.
5. **Finalize Design**: Test and adjust your footer to ensure it's responsive across different screen sizes.

Enjoy building your footer and exploring the capabilities of Tailwind CSS!


### Step-by-Step Solution Guide: Creating a Responsive Footer with Tailwind CSS

This guide will walk you through transforming the starter code into a complete, responsive footer using Tailwind CSS. Each step is designed to enhance your understanding of Tailwind's utility classes and responsive design principles.
#### Step 1: Set Up the Grid Layout

1. **Modify the Grid Container:** In the `div` with the class `grid`, replace `class="grid"` with `class="grid grid-cols-1 gap-6 sm:grid-cols-2 sm:gap-y-10 lg:grid-cols-4"`. This sets up a responsive grid layout with one column by default, two columns for small devices (`sm`), and four columns for large devices (`lg`).
#### Step 2: Style the Subscription Section

1. **Update Heading:** In the first `div` under `grid`, update the `h1` tag to include classes for text size, weight, and color. For instance: `class="max-w-lg text-xl font-semibold tracking-tight text-[#313131] xl:text-2xl dark:text-white"`.
2. **Style the Input and Button:** For the `input` tag, add classes to style the background, text, border, and focus states: `class="px-4 py-2 text-[#313131] bg-white border rounded-md dark:bg-[#313131] dark:text-white dark:border-[#313131] focus:border-[#d86943] dark:focus:border-[#d86943] focus:outline-none focus:ring focus:ring-opacity-40 focus:ring-[#d86943]"`. For the `button`, add classes to style its background, text, hover, and focus states.
#### Step 3: Style the Quick Links and Technologies Sections

1. **Add Styling to Headings:** In the next two `div` elements (Quick Link and Technologies), update the `p` tags to include classes for font weight and color.
2. **Style the Links:** For each `a` tag within these sections, add classes for text color, hover, and underline effects.
#### Step 4: Responsive Adjustments

1. **Flexbox for Mobile Views:** In the container `div` of the subscription section, update the `div` with the `flex` class to have a vertical layout on mobile and a horizontal layout on larger screens: `class="flex flex-col mx-auto mt-6 space-y-3 md:space-y-0 md:flex-row"`.
2. **Adjusting Grid Columns:** Ensure that the grid columns are set to span appropriately on different screen sizes using Tailwind's responsive prefixes (e.g., `sm:col-span-2`).

#### Step 5: Styling the Footer Bottom Section

1. **Horizontal Rule Styling:** Style the `<hr>` element to match the desired color and margin.
2. **Footer Bottom Flex Container:** In the `div` following the `<hr>`, use `class="flex items-center justify-between"` to align the items and distribute space evenly.
3. **Social Media Icons:** In the placeholder sections for social media icons, add appropriate classes for layout and styling.

#### Step 6: Testing Responsiveness

1. **Resize the Browser:** Test the responsiveness by resizing the browser window and observing how the layout adapts to different sizes.
2. **Use Developer Tools:** Utilize the responsive design mode in your browser's developer tools for more thorough testing on various device sizes.
#### Step 7: Final Touches

1. **Ensure Accessibility:** Make sure all elements are accessible, including appropriate `aria-labels` for screen readers.
2. **Validate HTML and CSS:** Use validation tools to ensure there are no errors in your HTML and CSS.

By following these steps, you will transform the starter code into a fully responsive and styled footer using Tailwind CSS. This exercise will not only reinforce your understanding of Tailwind's utility classes but also improve your skills in creating responsive web layouts.