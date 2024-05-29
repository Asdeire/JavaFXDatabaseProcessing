# JavaFX Database Processing

## Objective
The objective of this practical work is to implement a CRUD (Create, Read, Update, Delete) application using JavaFX with a single table in any RDBMS. The project will be managed using Maven, and it will also include asynchronous data loading and code style enforcement using Spotless.

## Overview
This practical work focuses on developing a desktop application using JavaFX. The application will demonstrate CRUD operations on a single database table with at least 7 attributes. The application will feature asynchronous data loading to improve UI responsiveness, and it will apply a modern visual style using a chosen JavaFX theme.

## Tasks
1. **Set up a Maven project in IntelliJ IDEA**:
    - Create an empty Maven project without using the JavaFX template.
    - Manually integrate JavaFX into the project.
    - Ensure the project can be compiled and run using the command `mvn clean javafx:run`.

2. **Create a database table**:
    - Define a table with at least 7 attributes in any RDBMS.
    - Populate the table with at least 50 test records using a specialized library like Java Faker.

3. **Integrate Spotless**:
    - Use Spotless via Maven to enforce Google code style conventions.

4. **Apply a visual style**:
    - Integrate a visual style for the application using Maven or CSS. Examples include MaterialFX, BootstrapFX, FluentFX, etc.

5. **Asynchronous data loading**:
    - Implement asynchronous data loading to avoid blocking the main (UI) thread.
    - Use `Task` or `CompletableFuture` to load data in a background thread and display a progress bar until the data is loaded.

## Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/my-crud-app.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd my-crud-app
    ```
3. **Build and run the application**:
    ```bash
    mvn clean javafx:run
    ```
4. **Populate the database**:
    - Ensure your RDBMS is running and accessible.
    - Modify `DatabaseUtils.java` to include your database connection details.
    - Run the database population script included in the project.

## Contribution Guidelines
Contributions to the development of the JavaFX CRUD Application are welcome. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature/new-feature
    ```
3. Make changes and commit them:
    ```bash
    git commit -m "Add new feature"
    ```
4. Push changes to your fork:
    ```bash
    git push origin feature/new-feature
    ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Additional Resources
- [JavaFX Documentation](https://openjfx.io/)
- [Spotless Maven Plugin](https://github.com/diffplug/spotless)
- [Java Faker](https://github.com/DiUS/java-faker)
- [MaterialFX](https://github.com/palexdev/MaterialFX)
- [BootstrapFX](https://github.com/kordamp/bootstrapfx)
