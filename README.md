### Challenge 1: The Kitchen Dish Pit - LIFO

``` The Scenario: You are writing code for a robotic dishwasher at a busy restaurant. 
    As waiters bring dirty plates back to the kitchen, they stack them on top of each other. 
    The robot can only ever grab the plate sitting on the very top of the stack so it doesn't break the others.
    Your Task: Write a function called wash_next_plate that accepts a Stack object of dirty plates. 
    If there are plates in the stack, remove and return the one from the very top to be washed. 
    If the stack is empty, return the string "All dishes clean". ```




### Challenge 2: The DMV Waiting Line - FIFO

``` The Scenario: You are writing the customer management software for the DMV. 
    When citizens walk in, they take a paper number and wait in the seating area. 
    To keep things perfectly fair, the service counter must call numbers strictly in the order people walked through the door. 
    Your Task: Write a function called call_next_number that accepts a Queue object containing ticket numbers (e.g., "A-101", "A-102"). 
    The function should remove the ticket number at the very front of the line and return a string format: "Now serving ticket [Number]". 
    If the room is empty and the queue has no numbers left, it should return "All customers served". ```




### Challenge 3: Music Playlist Search - Linked List (pointers)

``` The Scenario: You are building a music streaming app where user playlists are stored as a Linked List (where each song node points 
    to the next song). 
    A user wants to play a specific song, but you need to check if it actually exists in their playlist first.
    Your Task: Write a function called has_song that accepts the head_node of a playlist linked list and a target_title string. 
    Because you cannot look up elements by index in a linked list, your function must start at the head node and manually step through 
    the nodes one by one using the .next pointer. 
    Return True if you find a node with a matching title, or False if you reach the end of the list without finding it. ```
