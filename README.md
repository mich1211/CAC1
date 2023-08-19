CAC - 1
## Data Analytics




# MINI PROJECT REPORT




Prof. 
Kandula Balagangadhar Reddy






By
Noella Dsliva (22112004)
Michelle Dsouza (22112022)
3B.Sc DS A




# Movie Ticket Booking and Management Application
With the help of a python code, an application is created that stimulates a movie booking system. Through this application the user can book movie tickets along with personalized preferences from the given available movies. This code gives an easy understanding of how the ticket booking system is managed in order to make the process less complicated for the user. By importing CSV the data collected is stored in a structured format making it easy for accessing.

# Here is a detailed documentation of the code:


# Dependencies
The code uses the built-in csv module

# Reflection

Based on the provided code, here is a breakdown of the requirements for a movie ticket booking system:

1.	Movie Class:
•	Each movie has attributes such as serial number (Sr_no), title, duration, genre, time slots (time_slots), and available seats (available_seats).

2.	Booking Class:
•	Each booking has attributes such as customer name, movie title, time slot, and number of tickets.

3.	File Management:
•	The system uses CSV files to store movie data and booking information.
•	There are two files: "movies.csv" to store movie data and "bookings.csv" to store booking information.
.
4.	User Interface:
•	As mentioned earlier the system interacts with users through a command line interface (CLI) by displaying prompts and taking input for movie selection, customer name, time slot, seat selection, etc.
•	Users can choose a movie, enter their details, select seats, and make a booking.
•	After a successful booking, the system confirms the booking, displays the booking details.


# Functionality of each module and class

1. Movie Class:
    •	The Movie class represents a movie and has the following attributes:
      	Sr_no: The serial number of the movie.
      	title: The title of the movie.
      	duration: The duration of the movie.
      	genre: The genre of the movie.
      	time_slots: The available time slots for the movie.
      	available_seats: The number of available seats for the movie.
    •	The Movie class has a constructor method (__init__) that initializes these attributes.

2. Booking Class:
•	The Booking class represents a booking and has the following attributes:
•	customer_name: The name of the customer making the booking.
•	movie_title: The title of the movie being booked.
•	time_slot: The selected time slot for the booking.
•	num_tickets: The number of tickets being booked.
•	The Booking class has a constructor method (__init__) that initializes these attributes.

3. add_movie() Function:
•	This function creates a new Movie object and adds it to the list of movies.

4. add_booking() Function:
•	This function creates a new Booking object with the provided attributes and adds it to the bookings list.

5. save_movies_to_csv() Function:
•	This function saves the movie data to the `movies.csv` file in CSV format.

6. load_movies_from_csv() Function:
•	This function loads movie data from the `movies.csv` file and creates Movie objects.

7. display_movies() Function:
•	When this function is called, it displays the details of all the movies.

8. make_booking() Function:
•	With the help of this function a booking for a customer is made if the movie is available and there are sufficient seats.
•	This function also updates the available seats for the movie.
•	It saves the booking data to the `bookings.csv` file.
•	It also updates the movies and bookings data in the CSV files.

9. save_bookings_to_csv() Function:
•	This function saves the booking data to the `bookings.csv` file in CSV format.

10. load_bookings_from_csv() Function:
•	This function loads booking data from the `bookings.csv` file and creates Booking objects.

11. display_bookings() Function:
•	This function displays the details of all the bookings.

12. main() Function:
•	This function loads movies and bookings data from the CSV files.
•	It provides a command-line interface for the user to interact with the movie booking system.
•	Asks for the user's choice of movie, customer name, movie title, time slot, and number of tickets.
•	Displays the available seats for the chosen movie and asks for seat numbers.
•	Makes a booking if the conditions are met.
•	Displays the booking details and confirmation message.


# SUMMARY:
The Python code is implemented as a console-based application. It interacts with the user through the command line interface (CLI) by displaying options and taking input from the user. The application allows users to select a movie from the given available movies, Enter customer name, Enter a movie title, Enter time slot, Enter no. of Tickets, selection of seats to an Excel file. The code is well-commented to explain the functionality of each component.
