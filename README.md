# Restaurant-Automation

This project is an automation system developed to manage the daily operations of a restaurant. Developed with **.NET**, this system aims to help restaurant operators manage their business processes more efficiently. The project covers various functions from customer orders to menu management, from staff tracking to account management.

## Project Summary

### Features
- **Customer Order Management**: Manages customer orders from tables or online orders.
- **Menu Management**: Includes operations such as adding, editing and deleting menu items.
- **Staff Tracking**: Staff entry-exit tracking and management of task distributions.
- **Account Management**: Payments, invoice creation and tracking of daily income-expense reports.

## Installation and Operation

### Requirements
- Visual Studio 2019 or later
- .NET Framework 4.7.2 or later
- MSSQL Server

## Restaurant-Automation Related Images

### General Account Menu
![Ekran görüntüsü 2024-07-17 105149](https://github.com/user-attachments/assets/7784f409-821e-47d4-881d-03be2520f7ba)

### Customer Information Menu
![2](https://github.com/user-attachments/assets/a4f5c465-ff22-4c86-8e59-127afb9a7553)

### Installation Steps
1. Download the project files to your computer.

2. Open the project with Visual Studio.

3. Edit your database connection string in the `appsettings.json` file.

4. Create the necessary database on MSSQL Server.

5. Run the project and test it in your development environment.

### Go Live
1. Install the required .NET runtime version on the server.

2. Transfer your database to the server.

3. Upload the project files to the server and update your connection string in the `appsettings.json` file.

4. Publish your application and go live.

## Project Structure

- **Controllers**: The layer where the API endpoints for operations such as order management, menu editing, and employee management are defined.
- **Services**: Service layer where business logic is written and data management is provided.

- **Repositories**: Layer used to perform database operations.

- **Models**: Model classes for data such as customer, order, menu items, and staff.

## Topics to Learn

When you complete this project, you will have knowledge of the following topics:
- API Development with ASP.NET Core
- Layered Architecture Structure
- Using Repository Design Pattern
- Data Access with SQL and LINQ Queries
- Dependency Injection (DI)
- Developing Dynamic Web Projects Integrated with Database
- Invoice and Reporting Operations with .NET

## Technologies Used
- ASP.NET Core
- MSSQL
- Entity Framework
- SQL
- C#
- RESTful API

## Contributors
- **[Fahrettin Solak]** - Project development and management.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact
For any questions or feedback, please contact me at [fahsolak@gmail.com](mailto:fahsolak@gmail.com).

---

Good luck developing and bringing your project to live!


