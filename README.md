### One-page website for Ice-Cream Company

---

#### Layout:

Responsive, except for mobile devices. 

- **Breakpoints:** 
  - Mobile: flexible layout, becomes responsive at 480px.
  - Tablet: 768px.
  - Desktop: 1200px. 

- Validate layout in a validator. 
- Ensure semantic compliance with HTML5 standards. 
- Optimize vector and raster graphics. 
- Support retina displays. 
- Optimize image loading. 
- Add favicon.

---

#### Project Structure:

1. **Hero Header**
2. **Products**
3. **About**
4. **Advantages**
5. **Gallery**
6. **Customer Reviews**
7. **Contacts**
8. **Footer**

---

#### Hero Header:

- Logo, navigation menu, and button. 
- Logo displayed in PNG/SVG format. 
- Mobile and tablet menus: expandable sidebar. 
- Fixed sidebar, height equal to viewport. 
- Implemented with anchor links to corresponding sections. 
- “Buy now” button opens a modal window with an order form. 
- Form contains a bulleted list of products (with hidden checkboxes), inputs (with minimal data validation using the pattern attribute), and a Submit button. 
- Invalid data fields should be highlighted in red. 
- Validation should not occur until the user enters data. 
- “Ice cream made with passion” is the page title. 
- “Products” and “How it's made” buttons are anchor links to corresponding sections. 
- Set hero images absolutely. 
- Optionally, add an animation for their appearance on page load.

---

#### Products:

- “100% natural” is a title label, not a heading tag. 
- “Products” is the section title. 
- Design product cards as a grid of elements. 
- Product images are decorative, implement them using pseudo-elements. 
- Product names are headings. 
- The arrow button at the bottom of the card should open a modal window with a detailed product description and an order form.

---

#### About (How it’s made?)

- “Tradition and love” is a title label, not a heading tag. 
- “How it’s made?” is the section title. 
- The section contains a block with paragraphs and a "Read more" button. 
- The button should open a modal window with a full description of the product creation process, including a title, video (implemented using an iframe with a YouTube video), and a process description. 
- Set the decorative cow image absolutely, according to the mockup.

---

#### Advantages:

- No visible title in the section. 
- Create a hidden heading for crawlers. 
- The section contains a list of advantages, implemented as a grid of elements. 
- Implement advantage icons using pseudo-elements.

---

#### Gallery:

- Two-color background, implemented by positioning a background image according to the mockup. 
- Contentful image in the section. 
- Optionally, choose thematic ice cream images and implement their animated change.

---

#### Customer Reviews:

- A slider with customer reviews. 
- Bottom slide markers are page-by-page pagination for the slider. 
- If you connect a slider library to the project, you don't need to create them, they are automatically generated by the library. 
- You only need to style the pagination.

---

#### Contacts:

- No visible title in the section. 
- Create a hidden heading for crawlers. 
- The section contains a list of company representative offices, implemented as a grid of elements. 
- “Cafe” and “Food Truck” labels are not headings, but categories of representative offices. 
- Contact phone numbers and emails are implemented as links using communication protocols. 
- The “Our Locations” button should open a modal window with a contentful map image and a link to an external map resource. 
- The “Franchise” button should open a modal window with a form for the user to enter data, contact information for further communication, which includes inputs (with minimal data validation using the pattern attribute) and a Submit button.

---

#### Footer:

- The duplicated title does not need to be highlighted with a heading tag. 
- The footer contains a list of links to social networks. 
- Implement social network icons using svg-sprite. 
- Links should open the main social network page in a new tab. 
- The phone number must be implemented using communication protocols.
