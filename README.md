# task
unstop problem
Here’s a point-wise brief description of the code provided:

1. **Class Initialization (`__init__` method):**
   - A train coach is created with 10 rows of 7 seats and 1 row of 3 seats.
   - The seats are represented by `0` (available) or `1` (booked).

2. **Displaying Seats (`display_seats` method):**
   - This method displays the current seat layout of the train coach, showing the status of each seat (0 for available, 1 for booked).

3. **Checking Seat Availability (`is_seats_available_in_row` method):**
   - This method checks if there are enough consecutive seats (specified by `num_seats`) available in a given row.
   - It returns `True` if there are enough available seats, otherwise `False`.

4. **Booking Seats in a Row (`book_seats_in_row` method):**
   - This method books a specified number of consecutive seats (`num_seats`) in a given row if available.
   - It updates the seat status to `1` and returns `True` if the booking is successful.

5. **Finding and Booking Seats (`find_and_book_seats` method):**
   - The user requests a certain number of seats (`num_seats`) to be booked.
   - First, it tries to find available seats in one row. If successful, it books the seats.
   - If not, it books the seats across multiple nearby rows (if seats are available).
   - It limits the number of seats a user can book at once to 7.

6. **Example Usage:**
   - Initially, the seat layout is displayed.
   - Then, the user attempts to book 5, 7, and 10 seats in sequence, with each booking updating the seat layout, and the updated seat layout is displayed after each booking.


