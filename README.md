# Sanitary-ware-store-system
This is a Java-based application with an integrated GUI, database connection, and modular structure for managing various entities such as clients, orders, suppliers, employees, and vehicles.
---
## Project Structure
---
### Main Components
- **Java Files**: Backend logic and controllers
- **FXML Files**: Frontend layout definitions
- **CSS Files**: Application styling
- **SQL Scripts**: Database setup and connection
- **Image Resources**: Visual elements for the application
---
## File Descriptions
---
### FXML Files
- **AddOrder.fxml**: Layout definition for the "Add Order" feature.
- **clientView.fxml**: GUI layout for viewing client details.
- **DashBoard.fxml**: Main dashboard layout for navigating the application.
- **departmentView.fxml**: Layout for viewing department information.
- **Employees.fxml**: Interface for managing employee data.
- **new.fxml**: Placeholder for new feature GUI.
- **orders.fxml**: GUI for viewing and managing orders.
- **Products.fxml**: Layout for viewing and managing product data.
- **RegisterFxml.fxml**: Layout for the user registration form.
- **Sample.Fxml**: Example/sample GUI layout.
- **SearchCustomer.fxml**: GUI for searching customer details.
- **SearchProduct.fxml**: GUI for searching product details.
- **ShowOrder.fxml**: Layout for displaying order details.
- **Suppliers.fxml**: GUI for managing suppliers.
- **Vehicles.fxml**: Layout for vehicle-related data.
- **WarehouseView.fxml**: Layout for managing warehouse information.
---
### Java Files (Logic and Controllers)
- **AddOrderController.java**: Controls the functionality of `AddOrder.fxml`.
- **client.java**: Class defining client entity.
- **clientController.java**: Controller for client-related operations.
- **DashBoardController.java**: Controls the main dashboard's functionality.
- **DepartmentsController.java**: Logic for managing departments in the application.
- **EmployeesController.java**: Manages employee-related interactions.
- **Main.java**: Entry point for the application.
- **MyConnection.java**: Helper class for database connections.
- **mySqlConnect.java / mySqlConnector.java**: Database connectivity and configuration for MySQL.
- **Orders.java / OrdersC.java / OrdersController.java**: Classes and controllers for managing orders.
- **Products.java / ProductsController.java**: Classes and controllers for managing products.
- **RegisterController.java**: Handles user registration logic.
- **SampleController.java**: Example/sample controller.
- **SearchCustomerController.java**: Logic for searching customers.
- **SearchProductController.java**: Logic for searching products.
- **ShowOrderController.java**: Controls the "Show Order" functionality.
- **SuppliersController.java**: Handles supplier-related operations.
- **VehiclesController.java**: Manages vehicle-related functionality.
- **warehouseController.java**: Controls the warehouse management features.
- **Delivery.java**: Class for managing delivery details.
- **Customers.java**: Defines customer-related logic.
- **departmentEmployees.java**: Manages relationships between departments and employees.
- **departments.java**: Class defining department entities.
- **employees.java**: Employee class for managing employee data.
- **employeesPhones.java**: Handles employee phone details.
- **suppliers.java**: Supplier class for managing supplier data.
- **vehicles.java**: Class defining vehicle entities.
- **warehouse.java**: Manages warehouse-related data.
- **warehouseEmployees.java**: Defines relationships between warehouses and employees.
- **allInformationForClient.java**: Consolidates all relevant information for a client.
---
### CSS Files
- **application.css**: Global styling for the application.
- **buttons.css**: Styles specifically for button elements.
- **selected.css**: Highlight or selection-specific styles.
- **Style.css**: Additional application styling.
---
### SQL Script
- **itqansql.sql**: SQL script for initializing or managing the database schema.
---
### Image Resources (Located in `img/`)
- **Icons and Buttons**: Visual assets used throughout the application (e.g., `Add.png`, `search.png`, `truck.png`).
- **Warehouse Images**: Illustrative images for warehouses (e.g., `warehouse2.jpg`).
---
## How to Use
1. Clone the repository.
2. Set up a MySQL database using the `itqansql.sql` script.
3. Run the application via `Main.java`.
---
## Contribution
If you'd like to contribute, feel free to open an issue or submit a pull request.
---

Let me know if any descriptions need refinement or if you'd like me to add sections such as installation instructions or known issues.
