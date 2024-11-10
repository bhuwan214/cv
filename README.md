# CV Builder

CV Builder is a user-friendly, interactive web application designed to help users create a professional resume with ease. This tool allows users to input their personal details, education history, and work experience, which are instantly displayed in a formatted preview. The completed resume can be downloaded as a PDF, making it ready for job applications.

![CV Builder Screenshot](./Screenshot.png)

[Live Demo](https://bhuwan214.github.io/cv/)

## Features

- **Dynamic Real-Time Preview**: As users enter information, the CV preview updates immediately, allowing them to see how their resume will look in real-time.
- **Sectioned Layout**: Personal Details, Education, and Experience sections are organized and can be expanded or collapsed, making it easy to focus on specific parts while editing.
- **PDF Download**: Users can download the completed resume as a PDF document using the "Download" button, making it convenient to share or print.
- **Sample Data**: Load example data to see a sample resume layout, helping users understand the format and structure.
- **Clear All**: Clear all entered information to start over or remove unnecessary data.

## Technology Used

- **Vite + React**: The project is built with Vite for a fast development environment and React for efficient component-based UI. This combination ensures a snappy and reactive user experience.
- **FontAwesome**: Icons are used throughout the app for a visually appealing and intuitive interface, especially for collapsible sections and contact information.
- **React-to-PDF**: This library allows the application to render the preview as a downloadable PDF, making the resume easily accessible for offline use.

## Project Structure

- **components/**: Contains modular components such as `PersonalDetails`, `Education`, `Experience`, and `PreviewSection`. These components are reused and structured to provide a clear and maintainable codebase.
- **InputGroup**: A reusable component for form fields that provides consistent styling and behavior for all input elements across the app.
- **PreviewSection**: Displays a live preview of the resume, dynamically updating as users input their data.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhuwan214/cv.git
