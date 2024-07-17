
# MasterDetail

Welcome to the MasterDetail repository! This project demonstrates a Master-Detail pattern implementation in ASP.NET MVC.

## Overview

The Master-Detail pattern is a common UI design pattern used in many applications to display a list of items (master) alongside the details of a selected item (detail). This project serves as an example of how to implement this pattern effectively using ASP.NET MVC. The Master-Detail pattern is particularly useful in scenarios where users need to view and interact with a collection of related data items, such as customer orders, product listings, or inventory management systems.

### Key Features

- **Master View:** Displays a comprehensive list of items with essential information. Users can easily navigate through the list and select an item to view more details.
- **Detail View:** Provides in-depth information about a selected item. This view is dynamically updated based on the item selected in the master view.
- **CRUD Operations:** Supports Create, Read, Update, and Delete operations for items, allowing full control over the data.
- **Responsive Design:** Built with Bootstrap to ensure the application is accessible and functional on various devices, including desktops, tablets, and mobile phones.
- **Entity Framework Integration:** Utilizes Entity Framework for seamless database interactions, enabling efficient data management and querying.
- **SQL Server Database:** Stores item information securely and reliably using SQL Server, ensuring data integrity and performance.

## Technologies Used

- **ASP.NET MVC:** Framework for building web applications.
- **Entity Framework:** ORM for database interactions.
- **SQL Server:** Database for storing item information.
- **Bootstrap:** Front-end framework for responsive design.

## Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.7.2 or later
- SQL Server

### Installation and steps

1. Clone the repository:
   
   git clone https://github.com/abhishekalandikar/MasterDetail.git
   
   cd MasterDetail
   
2.Open the solution file MasterDetail.sln in Visual Studio.

3.Update the database connection string in Web.config

4.Apply migrations to create the database:

     Update-Database
  
5.Run the application:

     Ctrl + F5
  
### Usage

1.Navigate to the Master View to see the list of items.

2.Click on an item to view its details.

3.Use the buttons to create, update, or delete items.
