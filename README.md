# Lovers Bookstore

## Project Description

Lovers Books is an online book ordering system. Log in or register in order to choose your store location and books from our list of available titles. Once you are happy with your order, view your cart, which tells you your subtotal, and proceed to checkout. After submitting your order, place another order or log out. All of this functionality is styled in a clean and easy to read way.

## Technologies Used

* C#
* SQL Server
* ADO.NET Entity Framework
* HTML,
* JavaScript,
* CSS,
* Bootstrap
* DevOps
* Azure
* ASP.NET Core Web API

## Features

List of current features:
* Register and login functionality
* Client-side Validation
* Persistent data
* Ability to add multiple copies of a book to order

To-do list:
* Store and display customers' previous orders
* Add ability to edit cart and remove items from order
* Finalize styling 

## Getting Started
   
1. Ensure you have the .NET SDK installed (https://dotnet.microsoft.com/download).
2. Ensure you have Microsoft SQL Server Express installed (https://www.microsoft.com/en-us/sql-server/sql-server-downloads) and have selected the Local DB option.
3. Run in CLI: git clone https://github.com/03012021-dotnet-uta/TristynLinde_p1.git
4. Run in CLI: ./TristynLinde_p1/Repository
5. Change the connection string in LoversBooks/Startup.cs and Repository/loversContext.cs to match your server and desired database name.
6. Run in CLI: dotnet ef update database InitialCreate --startup-project ../LoversBooks/LoversBooks.csproj 
7. Run in CLI: cd ../LoversBooks
8. Run in CLI: dotnet watch run

## Usage

1. Create a new user with the information of your choice.
2. Select a store.
3. Add books to your order.
4. Click the "Cart" button to view your cart.
5. Click "Checkout" button.
6. Enter information
7. Logout

## License

This project uses the following license: MIT Licence (https://mit-license.org/).
