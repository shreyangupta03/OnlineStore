This is an online store implemented in C using Linux programming and system calls as a part of an Operating Systems course. The store has two user roles - Admin and User, and each role has different functionalities.

Admins can add, delete, or update products in the inventory. Users can see the list of products available, view their own cart, add or remove items from their cart, update quantities in their cart, pay for their cart, and generate a receipt for the same.

The program architecture consists of two programs - Server.c and Client.c. The server code, Server.c, communicates with the client code, Client.c, using sockets. The program uses file locking to prevent multiple accesses to the same file at the same time. The program stores customer data in customers.txt, cart data in orders.txt, product data in records.txt, and receipt data in receipt.txt.

To run the program, first compile the server code by running the command "gcc -o server Server.c" in the terminal. Then, run the server by executing "./server" in the same terminal. In a separate terminal, compile the client code by running "gcc -o client Client.c", and then run the client program by executing "./client". Follow the directions provided by the program to use the user or admin menu.

For more information on the implementation of this program, refer to the project report.