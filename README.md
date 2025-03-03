Inventory-app

Overview of the App 
The Inventory Management App was developed to help users efficiently track and manage their inventory. The primary goal was to provide an intuitive and user-friendly interface for adding, updating, searching, and filtering inventory items based on item ID and date. This app was designed to address the need for organized inventory tracking, particularly for small business owners and individuals who require a simple way to monitor stock levels and receive alerts for low inventory.

User-Centered UI Design
To ensure a user-friendly experience, the app includes key screens and features such as:  
- A Login and Registration Screen for secure access.  
- An Inventory Dashboard that displays inventory items in a structured GridLayout with headers.  
- A Search Functionality that allows users to find items by ID while maintaining a consistent grid display.  
- A Date Picker Feature to filter inventory based on selected dates.  
- A Low-Stock Alert System that highlights items with critically low stock.  
- Edit and Delete Options accessible via long press and tap actions.  

The UI was designed with clarity and responsiveness in mind, ensuring that inventory items remain properly formatted while buttons and input fields remain accessible. By using consistent spacing, colors, and text formatting, the design successfully enhances usability.

Approach to Development
The app was developed using Kotlin and Android Studio, with SQLite as the database for storing inventory data. A modular approach was followed, breaking down the app into key components such as user authentication, database interactions, and UI management.  
- Encapsulation and Reusability: Functions such as `createGridTextView()` were implemented to dynamically create UI elements, ensuring code reusability.  
- Efficient Data Handling: The app leverages `GridLayout` for structuring data but could benefit from `RecyclerView` in future iterations for better scalability.  
- Database Management: SQLite was used for persistent storage, with proper queries for fetching and updating records.

These techniques ensure scalability and can be applied in future projects for maintaining clean, modular, and efficient codebases.

Testing and Debugging 
The app was tested through various methods:  
- Manual UI Testing to check for responsive layout adjustments as inventory grows.  
- Functionality Testing for core features such as adding, updating, deleting, and filtering items.  
- Database Testing to verify that entries were stored correctly and retrieved accurately.  
- Error Handling Checks to prevent crashes, such as validating inputs before database insertion.  

Testing was critical in revealing issues such as misalignment of grid elements, incorrect date formatting, and unexpected UI shifts when adding multiple rows. Fixing these issues helped improve both performance and user experience.

Challenges and Innovations  
One major challenge was ensuring that inventory items remained aligned properly in the GridLayout as more data was added. The solution involved using weighted column spacing and dynamic text formatting to maintain consistent styling. Additionally, filtering by date initially displayed "Selected Date: YYYY-MM-DD" instead of the actual date, which was corrected by extracting only the date string for database storage.

Success in Demonstrating Skills  
The most notable success in this project was the implementation of an interactive and structured inventory grid with functional search and filtering. The ability to maintain a clear, structured UI while handling dynamic data showcases strong UI design principles, database management, and Kotlin development expertise. Additionally, incorporating error handling, input validation, and notification features strengthened the overall robustness of the app.

This project provided valuable experience in real-world app development, reinforcing the importance of structured planning, iterative testing, and user-focused design in mobile applications.
