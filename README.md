**Abstract:** This is a user-friendly app that allows users to create, save, and view motivational posters. With the click of a button, users can generate random posters for inspiration or design their own by inputting custom images, titles, and quotes. Adding to the interactivity, users can also save their favorite posters for future inspiration.

**The features included are:**
- The ability to create custom posters with user-defined images, titles, and quotes.
- The ability to view randomly generated motivational posters.
- The ability to save favorite posters for later inspiration.

**Installation Instructions:**
1. Git clone this repo to your local machine.
2. Cd into that directory.
3. Enter the command `open index.html` to open the app in your browser.
4. Have fun looking!

**Preview of App:**
![Hang In There Poster Project](https://amysiu1028.github.io/PosterWebProject/)
<img width="745" alt="Screen Shot 2023-09-27 at 1 56 39 PM" src="https://user-images.githubusercontent.com/140124108/271075006-da2eb0b0-f09f-4127-90ce-2da313d2c91c.png">
<img width="801" alt="Screen Shot 2023-09-27 at 1 57 16 PM" src="https://user-images.githubusercontent.com/140124108/271074715-eb91672a-428d-4574-8aa9-1d61d3f3f97a.png">
<img width="818" alt="Screen Shot 2023-09-27 at 1 56 57 PM" src="https://user-images.githubusercontent.com/140124108/271074713-5f17d411-f1f0-488e-838d-f7051943eadb.png">
<img width="801" alt="Screen Shot 2023-09-27 at 1 57 22 PM" src="https://user-images.githubusercontent.com/140124108/271074720-8447288d-d9ad-4994-b11c-505b9295d92c.png">



**Contributors:** 
- [Amy](https://github.com/amysiu1028)


**Learning Goals:**
- Gain proficiency in JavaScript.
- Understand the connection between HTML, CSS, and JavaScript.
- Practice collaborative coding and version control.
- Enhance problem-solving skills.
- Improve code readability and maintainability.

**Wins:**
- Successfully implemented the core functionality of creating, saving, and viewing posters.
- Achieved a clean and user-friendly interface.
- Effectively collaborated with team members.
- Gained a deeper understanding of JavaScript and DOM manipulation.

**Challenges:**
- Debugging certain aspects of the application's functionality.
- Managing the transition between different views in the app.
- Ensuring responsive design and compatibility across browsers.

**Observations & Questions:**

*Observations:*
- This project provided valuable hands-on experience with JavaScript and web development.
- Collaborative coding helped improve team communication and code quality.
- The separation between data model and DOM representation was crucial for code organization.

*Github Questions:*
- How can we further optimize our GitHub workflow for future projects?
- Are there any additional GitHub features or best practices we should explore?

*Terminal Questions:*
- What are some advanced Git commands or strategies that can enhance our version control process?
- How can we streamline our terminal commands for a more efficient development workflow?

*Coding Questions:*
- How can we improve the error handling and validation in the form input fields?
- Are there any opportunities for code refactoring to make the application more efficient and readable?

## 💡 Iterations:

### **Iteration 0: Project Setup and Main Page**
- Initialize the project by forking and cloning the repository.
- Examine the existing codebase to understand its structure.
- Ensure all team members and the instructor are collaborators on the repository.
- Create the main page with a randomly selected poster, image, title, and quote.
- Implement the "Show Random Poster" button to display a new random poster when clicked.

### **Iteration 1: Switching Views**
- Build the form view for creating custom posters and the saved posters view.
- Implement functionality to hide the main poster and show the appropriate view when buttons are clicked.
- Enable users to switch between the main poster, form, and saved posters views seamlessly.

### **Iteration 2: Creating a New Poster**
- Develop the new poster form view where users can input images, titles, and quotes.
- Implement the "Show My Poster" button to create a new, unique poster object and save the submitted data.
- Ensure the form view transitions back to the main poster view, displaying the newly created poster.

### **Iteration 3: Saving & Viewing Posters**
- Create functionality to save the current main poster to the savedPosters array when the "Save This Poster" button is clicked.
- Prevent duplicate saves of the same poster.
- Build the "Show Saved Posters" view to display all posters in the savedPosters array.

### **Iteration 4: Deleting Saved Posters**
- Add the ability to delete a saved poster when a user double clicks it.
- Implement this functionality without using HTML `onclick` attributes; instead, use JavaScript.

## 💡 Extensions (Optional):

- Implement data validation and error handling in the form.
- Allow users to click individual parts of the main poster (image, title, quote) to update them with random items.
- Create a modal to view saved posters in larger detail.
- Enable users to drag and drop saved posters to reorder them.
- Explore additional features that enhance user experience without breaking existing functionality.


