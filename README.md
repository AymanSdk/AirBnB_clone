# Airbnb Console Clone in Python

![Airbnb Console Clone](./Assests/Screenshot%202023-11-20%20130658.png)

**Airbnb Console Clone** is a Python command-line interface (CLI) application that emulates some functionalities of the Airbnb project. This console allows users to interact with a simulated Airbnb environment, creating, managing, and manipulating property listings and user accounts.

## Getting Started

To run the Airbnb Console Clone, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AymanSdk/AirBnB_clone.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd AirBnB_clone
   ```

3. **Run the application:**
   ```bash
   ./console.py
   ```

## Features

### 1. Creating Instances

- Use the `create` command to generate new instances of various classes like User, Place, State, City, Amenity, and Review.
- Example:
  ```bash
  create User
  ```

### 2. Viewing Instances

- Utilize the `show` command to display information about a specific instance based on its class and ID.
- Example:
  ```bash
  show User 1234-5678
  ```

### 3. Deleting Instances

- Remove instances using the `destroy` command by specifying the class name and instance ID.
- Example:
  ```bash
  destroy Place 8765-4321
  ```

### 4. Listing Instances

- View all instances or instances of a specific class using the `all` command.
- Example:
  ```bash
  all
  all Place
  ```

### 5. Updating Instances

- Modify attributes of an instance using the `update` command with the class name, ID, attribute, and new value.
- Example:
  ```bash
  update User 1234-5678 first_name "John"
  ```

### 6. Counting Instances

- Obtain the count of instances or instances of a specific class using the `count` command.
- Example:
  ```bash
  count
  count State
  ```

### 7. Exiting the Console

- Use the `quit` or `Ctrl + D` to exit the console.

## Project Structure

The project consists of a single Python script:

- `airbnb_console.py`: Contains the main Airbnb Console Clone implementation using the `cmd` module.

## Contributing

Contributions to the Airbnb Console Clone are welcome. If you encounter issues or have ideas for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/yourusername/airbnb-console-clone).

## Disclaimer

This console is developed for educational purposes and lacks full features and security measures found in a production environment.

**Use at your own risk.**

---

Explore and experiment with the Airbnb Console Clone! If you have any questions or issues, feel free to reach out to the project contributors.
