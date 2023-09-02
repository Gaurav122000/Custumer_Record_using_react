# Custumer_Record_using_react
In this app I used form to get the details of the customers, like the guest count, name, and phone number.

# Working:-
When the form is submitted, then "Seats Left" decrease by the guest count, and a new entry appear at the top of the table having a blank "Check Out" column and the status show "Click to Checkout".
After clicking on "Click to Checkout", the user checked out, and the "Check Out" column show the current timestamp as the checkout time. Also, "Seats Left" increase the guest count.

Clicking on "Delete" in the "Remove Entry" column delete the record. If it's already checked out and when delete is clicked, then "Seats Left" did not increase, but if the record is deleted before checking out, then "Seats Left" get increase by the guest count.
When the count of guest exceeds "Seats Left" show an alert with the message "Guest count exceeds capacity". Also the "Seats Left" never exceed "Total Capacity" or have a negative value.
