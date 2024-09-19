
# Rick and Morty Character Feed

## Description

This is a React-based application that fetches, displays, and manages a list of characters from the Rick and Morty API. It supports sorting, filtering, and pagination functionalities. Each character is displayed in a styled card layout, and users can navigate through pages and adjust sorting and filtering options.

## Features

1.Character Display: Shows a list of characters with their name, species, status, gender, and date created.

2.Sorting: Sort characters by name or date created.

3.Filtering: Filter characters by status (All, Alive, Dead, Unknown).

4.Pagination: Navigate through pages of characters.

## Technologies Used

1.React

2.Axios (for API requests)

3.CSS (for styling)


### Prerequisites

Node.js and npm (Node Package Manager) installed on your machine. You can download them from [Node.js official website](https://nodejs.org/).

### Installation

1. Clone the repository:
   
   git clone https://github.com/yeamoon/post-feed.git


3. Navigate to the project directory:

 
   cd post-feed
 

4. Install the dependencies:

 
   npm install


### Running the Application

1. Start the development server:


   npm start


2. Open your browser and navigate to http://localhost:3000 to see the application in action.


### Running the  Built application


Navigate to the project directory : cd post-feed
Navigate to the Branch:  Production_Builds

Run:   npm install -g serve
       serve -s build


## File Structure

   src - Contains the source code for the application.
   Pages - Contains React components.
   CharacterPage.jsx - Main page component that fetches and displays the characters.
   CharacterCard.jsx - Component for displaying individual character cards.
   SortingAndFiltering.jsx - Component for sorting and filtering options.
   ErrorMessage.jsx - Component for displaying error messages.
   App.jsx - Main application component.
   public/ - Contains static files and the `index.html` file.
   package.json - Contains project metadata and dependencies.

## Styling

Character Cards: Styled with CSS to include circular images and information boxes with various styles.
Pagination Controls: Styled to be modular and user-friendly.

## Acknowledgments

[Rick and Morty API](https://rickandmortyapi.com/) - For providing the character data.
[React Documentation](https://reactjs.org/docs/getting-started.html) - For React guidelines and best practices.


