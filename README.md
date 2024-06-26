## Flask Application Design for Japanese Language Learning with Images

### HTML Files
- **index.html**: The main interface page where users can interact with the application, including viewing Japanese words and their corresponding images.
- **word_form.html**: A form page where users can add new Japanese words and their associated images to the application.

### Routes
- **index**: Renders the `index.html` page and displays the list of Japanese words and their images.
- **new_word**: Renders the `word_form.html` page, allowing users to input a new Japanese word and its image.
- **add_word**: Processes the form submission from `word_form.html`, adding the new word and image to the application's database.