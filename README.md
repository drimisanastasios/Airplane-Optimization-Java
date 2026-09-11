# Airplane Optimization Program

The **Airplane Optimization** application uses a VRP (Vehicle Routing Problem) optimization algorithm and the Haversine formula to calculate optimal flight paths based on destination data and user-defined parameters.

## Execution Instructions

Follow the steps below to run the application.

### 1. Running via GitHub

If you have a GitHub account:
- Visit the [GitHub repository](https://github.com/AnastasiosDrimis/My-Project-Repository).
- Copy the repository URL.
- In your terminal (`cmd`), execute the following commands:

`git clone https://github.com/AnastasiosDrimis/My-Project-Repository.git`  
`cd My-Project-Repository`  
`cd airplaneoptimization`  
`cd src`  
`cd main`  
`cd java`  
`cd com`  
`cd codewarrios`  
`java CombinedApplication`  

### 2. Running without GitHub

If you don't use GitHub:
- Visit the [GitHub repository](https://github.com/AnastasiosDrimis/My-Project-Repository).
- Click the **Code** button and select **Download ZIP**.
- Extract the ZIP file on your computer.
- Open the project folder and execute the `.jar` file (located in the `target` folder).

### 3. Running via Command Line

If you have the `.jar` file, you can run it directly using the following command:

`java -jar airplaneoptimization-1.0-SNAPSHOT.jar`

## Application Overview

### Login

Upon launching the application, the **Login** window will appear. You can log in using the following default accounts:
- **User:**
  - Username: `user`
  - Password: `user123`
  
- **Administrator (admin):**
  - Username: `admin`
  - Password: `admin123`

### Admin Management

When logged in as an **admin**, the administration panel provides functionality to:
- Create new users/admins with unique credentials.
- Add new airports by entering the required parameters.

In case of invalid data entry, the program displays appropriate error messages. As long as the application remains open, you can log in with newly created accounts and view newly added destinations in the list.

### User Operations

When logged in as a **user**, the system prompts you to enter:
1. The number of airplanes available.
2. The number of destinations to include.

A table displaying available destinations will then appear. Select your desired destinations by holding down the **Control** key while clicking each item. After clicking **Submit**, the system displays:
- The assigned airplanes.
- The calculated flight routes.
- The total distance (in kilometers) traveled by each aircraft.

### Repository Structure

- **`airplaneoptimization/`**: Contains all core project source files.
- **`LICENSE`**: Includes the application's software license details.
- **`umlairplaneoptimization.png`**: The UML diagram image.
- **`README.md`**: Project documentation file.

### Input Validation

The program includes built-in error handling and displays meaningful warning messages if invalid input is provided.

## Technical Details

Key implementation features:
- **Arrays**, **lists**, **variables**, **methods**, and **classes** for data storage and management.
- **Haversine formula** to calculate precise distances between destinations using geographical coordinates (latitude and longitude).
- A simplified **VRP (Vehicle Routing Problem)** algorithm to solve route optimization.

## UML Diagram

![UML Airplane Optimization](umlairplaneoptimization.png)

## Prerequisites & Troubleshooting

- Ensure that **JDK (Java Development Kit)** is installed on your system to compile and execute Java commands.
- If the application fails to run, verify that input parameters and credentials are correctly formatted.

## License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.
