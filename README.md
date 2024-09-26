# Personal Portfolio Assignment

Welcome to the Personal Portfolio Project! Your goal is to create a simple, static personal portfolio website using HTML and CSS. You will work within the `src` folder provided to you.

## Project Structure

Inside the `src` folder, you will find the following starting files:
```
  src/
  ├── index.html         # Your main landing page
  ├── css/
  │   └── style.css      # Your main CSS file, external styles should go here
  └── images/            # Store your images here (optional)
```

### Instructions

1. **Create Your Portfolio Pages**:
   - Begin by editing the `index.html` file. This will be your portfolio's landing page.
   - Create at least **2 additional HTML pages** (such as `about.html`, `projects.html`, etc.) that showcase your work experience, projects, education, hobbies, or other personal details.
   - Ensure that **all pages are connected via a navigation menu** with links to the other pages.
  

   Example:
   ```html
   <nav>
     <ul>
       <li><a href="./index.html">Home</a></li>
       <li><a href="./about.html">About</a></li>
       <li><a href="./projects.html">Projects</a></li>
     </ul>
   </nav>
   ```

2. **Design Your CSS Stylesheet**:

  - In the `src/css` folder, you will also find the style.css file. Use this file to define the styles for your HTML pages. You should apply consistent styling across all pages for headers, footers, navigation, and content sections.
  - Make sure to use proper CSS practices such as:
    - Use external styles (in the style.css file) rather than inline styles.
    - Utilize selectors, classes, and IDs appropriately.
    - Ensure your styles create a visually appealing and consistent layout across all pages.

3. **File Structure**: 
  Ensure that your files are organized as follows:
    ```
      src/
      ├── index.html         # Your main landing page
      ├── about.html         # Example: An about page (create your own additional pages)
      ├── projects.html      # Example: A projects page (create your own additional pages)
      ├── css/
      │   └── style.css      # Your main CSS file, external styles should go here
      └── images/            # Store your images here (optional)
    ```

## Assignment Requirements

For this assignment, you are expected to create a personal portfolio website. Below are the detailed requirements for both **HTML** and **CSS** components of your project, based on the rubric.

### HTML Requirements

1. **At least 3 HTML pages** including the landing page (5 pt).
   - Suggested pages include: About Me, Projects, Work Experience, Education, Hobbies, etc.

2. **Title and Favicon** (3 pt).
   - All pages should have a title and a visible favicon on the browser tab.

3. **Consistent Header** (5 pt).
   - A consistent header should span the full width of all pages.

4. **Navigation Menu** (10 pt).
   - A navigation menu should be present on all pages with links to other pages of your site.

5. **Footer** (10 pt).
   - A footer should be included on all pages with:
     - Copyright information.
     - Icons linked to your GitHub profile (social media icons are optional).
     - An icon that opens a new outgoing email message to your Northeastern email address.

6. **Image with Caption** (4 pt).
   - Add your image to your homepage with a caption.

7. **Master's Course List** (3 pt).
   - Include a list of all your Master's courses on a page with relevant content.

8. **Northeastern Logo** (3 pt).
   - Add a Northeastern logo image on a page and link it to the Northeastern website.

9. **Use Semantic Tags**.
   - Use proper semantic tags to structure your HTML code.

10. **W3C Validation** (10 pt).
   - All HTML pages should be validated using the [W3C validator](https://validator.w3.org/).

### CSS Requirements

1. **External Styling** (2 pt).
   - Use external styling through the `style.css` file located in the `src/css` folder.

2. **Pseudo-Classes and Pseudo-Elements** (5 pt).
   - Include pseudo-classes (e.g., `:hover`, `:visited`) and pseudo-elements (e.g., `::before`, `::after`) in your CSS.

3. **Background Image** (5 pt).
   - Add a background image to at least one page.

4. **Text Area Width** (5 pt).
   - Make the visible text area **80% of the viewport's width**.

5. **Navigation Styling** (5 pt).
   - Give the navigation area a background color and make the text center-aligned.

6. **Visited Links Color** (5 pt).
   - Assign a custom color (different from the browser's default) to visited links.

7. **Google Fonts** (5 pt).
   - Use Google Fonts to enhance typography in your project.

8. **Anchor Links**.
   - Include at least one anchor link (`<a>`) that links to a specific section within the same page using an `id`.

9. **Box-Sizing Behavior**.
   - Adjust the box-sizing behavior so that the browser calculates an element’s total width and height, including its borders and padding (use `box-sizing: border-box`).

### File Structure Requirements

1. **Proper File Structure** (5 pt).
   - Your project must have a proper file structure:
     - CSS files should be placed in a subdirectory called `css` within the `src` folder.
     - Images should be placed in a subdirectory called `images` within the `src` folder.

### Additional Notes

- You are encouraged to design a portfolio that you are proud to share with your friends.
- You may use icons from [FontAwesome](https://fontawesome.com/) to enhance your design.


### Do Not Modify files outside `src` Folder
  - **Important**: Do not **modify** any of the files outside the `src` folder. This folder contains the automated tests that will be used to check your project against the assignment requirements. Any changes to the files in the `test` folder may result in incorrect test results or disqualification of your submission.


