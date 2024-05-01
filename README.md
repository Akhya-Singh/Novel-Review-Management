# Novel Review Management System

This is a Java application that allows users to store and manage reviews for novels. Users can enter the name of the novel, rate it out of 10, and provide the price. The application stores this information in a MySQL database.

## Features

- User-friendly GUI built with Java Swing
- Database connectivity with MySQL
- Store novel name, rating, and price
- Submit and save novel reviews

## Prerequisites

- Java Development Kit (JDK) installed
- MySQL server installed and running

## Getting Started

1. Clone the repository:

```
git clone https://github.com/Akhya-Singh/Novel-Review-Management-System.git
```

2. Set up the MySQL database:
   - Create a new database named `db1`.
   - Create a table named `novels` with columns `Rate` (for price), `Name`, and `Ratings`.

3. Update the database credentials in the `NewJFrame.java` file:

```java
con = DriverManager.getConnection("jdbc:mysql://localhost:3306/db1", "your-username", "your-password");
```

Replace `"your-username"` and `"your-password"` with your MySQL username and password, respectively.

4. Build and run the application using your preferred Java IDE or by compiling the source code from the command line.

## Usage

1. Launch the application.
2. Enter the name of the novel in the provided text field.
3. Rate the novel out of 10 in the corresponding text field.
4. Enter the price of the novel in the designated text field.
5. Click the "Submit" button to save the novel review to the database.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.

## Acknowledgments

- The development team: Aryan Shambharkar, Akhya Singh, and Manan Variya.
- Shah and Anchor Kutchhi Engineering College for providing the project opportunity.
