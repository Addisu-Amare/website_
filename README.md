# Quarto Positron Site

This is a Quarto project designed to create an academic website using the Positron theme. The website includes various sections such as publications, teaching, research, and a blog.

## Project Structure

- **_quarto.yml**: Main configuration file for the Quarto website.
- **index.qmd**: Homepage of the website.
- **about.qmd**: Information about the author and the purpose of the website.
- **publications.qmd**: A list of the author's publications.
- **teaching.qmd**: Details about the author's teaching activities and courses.
- **research.qmd**: Description of the author's research interests and projects.
- **projects/project-example.qmd**: Details of a specific project.
- **blog/post-1.qmd**: A blog post related to the author's academic work.
- **_bibliography/publications.bib**: BibTeX file for managing bibliographic references.
- **data/sample-dataset.csv**: Sample dataset for examples or demonstrations.
- **css/styles.css**: Custom CSS styles for the website.
- **scripts/site.js**: JavaScript code for interactivity.
- **.gitignore**: Specifies files to be ignored by Git.

## Setup Instructions

1. **Install Quarto**: Ensure you have Quarto installed on your machine. You can download it from [quarto.org](https://quarto.org).

2. **Clone the Repository**: Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:
   ```
   cd quarto-positron-site
   ```

4. **Render the Website**: Use the following command to render the website:
   ```
   quarto render
   ```

5. **Serve the Website Locally**: To view the website locally, use:
   ```
   quarto serve
   ```

## Usage

- Modify the `.qmd` files to update content for each section of the website.
- Update the `_quarto.yml` file to change site-wide settings such as the title and author information.
- Add new blog posts in the `blog` directory and update the index as necessary.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.