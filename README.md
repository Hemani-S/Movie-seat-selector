                                                        Movie Seat Selector
A simple web application for selecting and booking seats for a movie. The app allows users to select a movie, choose available seats, and view the total price. The seat and movie selection data is saved using localStorage, so users can revisit their previous selections.

         Features
1. Dynamic movie selection with corresponding ticket prices.
2. Interactive seat selection with real-time updates on the number of selected seats and the total price.
3. Seat selection status saved in localStorage, allowing persistence across page reloads.
4. Seats are categorized as Available, Selected, and Sold.

   
          Technologies Used
HTML5: For structuring the webpage.
CSS3: For styling the page, including hover effects and responsive design.
JavaScript (Vanilla JS): For managing the seat selection logic, updating the DOM, and handling localStorage.


          How It Works
Movie Selection:

Users can choose from a dropdown list of movies. Each movie has a different price.
Seat Selection:

Available seats are shown in a grid, where users can click to select or deselect seats.
Sold seats are marked and cannot be selected.
The number of selected seats and total price updates dynamically.
Local Storage:

The app stores the selected seats and movie information in localStorage. This means that even if you refresh the page, your selections will persist.
