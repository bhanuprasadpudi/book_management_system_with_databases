# book_management_system_with_databases

Movie Database Management System:

Overview:
This Python program allows users to manage a movie collection using an SQLite database. It provides functionalities for adding movies, displaying movie details, marking movies as watched, searching for movies based on different criteria, updating movie information, and deleting movies. The user interacts with the system through a menu interface. Overall, it offers a comprehensive solution for organizing and tracking movie data.

Description:
This Python program allows users to manage a movie collection using an SQLite database. Let’s break down its functionalities:

	.Database Connection and Table Creation:
		.The program connects to an SQLite database named moviess.db.
		.It creates a table called MOVIES with columns for movie title, director, release year, IMDb rating, and whether the movie has been watched.
	.Adding Movies:
		.The add_movie() function prompts the user for movie details (title, director, year, and rating).
		.It inserts the entered data into the MOVIES table.
	.Displaying Movies:
		.The show_movies() function retrieves all rows from the table and displays movie details.
		.It includes information about whether a movie has been watched.
	.Marking Movies as Watched:
		.The movie_watched() function prompts the user for a movie title.
		.It updates the corresponding row in the table to set the WATCHED column to True.
	.Searching for Movies:
		.The find_movie() function allows users to search for movies based on different criteria (title, director, year, or rating).
		.Users input their choice (‘t’, ‘d’, ‘y’, or ‘r’) and specific details to search for movies.
	.Updating Movie Details:
		.The update_movie() function lets users modify movie details (title, director, year, or rating).
		.Users choose which aspect to update and provide new values.
	.Deleting Movies:
		.The delete_movie() function removes a movie from the database based on its title.
	.Clearing the Entire Movie List:
		.The clear_movies() function deletes all records from the MOVIES table.
	.Menu Interface:
		.The menu() function provides a user-friendly menu where users can select different actions.
		.It loops until the user chooses to quit (‘q’).
Overall, this code offers a comprehensive solution for managing movie data.

Tools used:
	.Jupyter Notebook(anaconda)
	.SQLite

Conclusion:
	In conclusion, the Python code serves as a robust movie database management system. It allows users to add movies, display movie details, mark movies as watched, search for specific movies, update movie information, and even delete movies. The menu-driven interface enhances usability, making it a comprehensive solution for organizing and tracking movie data.
