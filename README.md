# Flatdango

Flatiron Movie Theater is open for business! You will be building out an
application, Flatdango, that allows a user to purchase movie tickets from the theatre.

### Core Deliverables
As a user, I can:

I) See the first movie's details, including its poster, title, runtime, showtime, and available tickets when the page loads. The number of available tickets will need to be derived by subtracting the number of tickets_sold from the theater's capacity.

II) See a menu of all movies on the left side of the page in the ul#films element when the page loads. 

III) Buy a ticket for a movie. After clicking the "Buy Ticket" button, I should see the number of available tickets decreasing on the frontend. I should not be able to buy a ticket if the showing is sold out (if there are 0 tickets available). A persistence mechanism is needed for this feature.

When a ticket is purchased, the app should:
   Persist the updated number of tickets_sold on the server.

IV) Delete a film from the server. Add a delete button next to each film in the ul#films menu. When the button is clicked, remove the film from the list and also delete the film on the server:

V) When a movie is sold out (when there are no available tickets remaining), indicate that the movie is sold out by changing the button text to "Sold Out". Also update the film item in the ul#films menu by adding a class of sold-out to the film. For reference, here's what the contents of the ul#films element should look like with a sold out film:

<li class="film item">(Title of film)</li>
<li class="sold-out film item">(Title of a sold-out film)</li>
<li class="film item">(Title of film)</div>