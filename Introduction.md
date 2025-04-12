# Paper-Hearts-GUI
<p align="center">
  <img src="References/paper-hearts.png" alt="Bookstore Logo" width="300"/>
</p>

---
## Background 
Paper Hearts is a bookstore located in Little Rock, Arkansas with a mission of selling books that readers can connect
with in an environment that fosters joy, community, acceptance, and meaningful conversation. The Paper Hearts GUI is a personalized book recommendation system designed for customers of Paper Hearts Bookstore. The application allows users to input their reading preferences and receive immediate book recommendations based on their preferences. The system also tracks customer input for future recommendations, enhancing the personalized experience over time.

## Features

- **Personalized Book Recommendations**: Customers receive immediate book suggestions based on their input.
- **Data Tracking**: The system records user preferences to improve recommendations for future visits.
- **Data Import**: The application imports book data from Excel files to keep the recommendation database updated.
- **Potential External Links**: Book recommendations may include links to external websites for more information or purchasing options.

## Technologies Used

- **Python**: Core programming language used to implement the application logic.
- **SQLite**: Lightweight database used for storing customer data and book information.
- **Pandas**: Data manipulation library used to import and process data from Excel files.

## How It Works

1. **User Input**: Customers provide their book preferences (e.g., genre, author, past reads).
2. **Data Processing**: The application analyzes user input and compares it against the existing database.
3. **Recommendation Generation**: A personalized book recommendation is generated and displayed, potentially including a link to an external website for more details or purchasing options.
4. **Preference Tracking**: The system stores customer preferences for future recommendations, improving over time.

## Data Input and Output

- **Input**: Book information is imported from Excel files, including metadata like genre, author, and popularity.
- **Output**: The application generates a book recommendation in plain text

✨ **Special thanks to Paper Hearts for allowing their real data to be used for this project. To protect the bookstore's information, fake customer names and emails were generated and access to the raw data or displays of the raw data will not be provided. Python code has also be edited to prevent real data names from being seen. Thank you for your understanding. This project was completed as part of a class assignment with a partner. Responsibilities and efforts were shared equally**✨
