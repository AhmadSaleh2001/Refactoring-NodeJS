# DRY-Principle

This project utilizes Node.js, Express, and Sequelize to implement the DRY (Don't Repeat Yourself) principle. It follows a specific folder structure that includes a `service` directory containing classes and code for the business logic. The main class in this structure is called `Service`, which accepts a `SequelizeModel` and provides four CRUD operations. Additionally, `userService` and `orderService` extend the `Service` class to handle user and order-related operations.

## Folder Structure

The project follows a specific folder structure for implementing the DRY principle:

- `service`: This folder contains classes and code for the business logic.
- `Service.js`: The main class that accepts a `SequelizeModel` and provides four CRUD operations.
- `userService.js`: Extends the `Service` class to handle user-related operations.
- `orderService.js`: Extends the `Service` class to handle order-related operations.
- `controllers`: This folder contains the general `CRUDController` to reduce code duplication.
- `CRUDController.js`: Accepts an instance of `userService` or `orderService` and applies different operations.

## Contributing

Contributions are welcome! If you find any issues or would like to add new features, please feel free to submit a pull request.
