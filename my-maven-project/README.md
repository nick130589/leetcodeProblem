# My Maven Project

This is a basic Java Maven project structured for solving problems on LeetCode. 

## Project Structure

```
my-maven-project
├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── leetcode
│   │               └── problem
│   │                   └── App.java
│   └── test
│       └── java
│           └── com
│               └── leetcode
│                   └── problem
│                       └── AppTest.java
├── pom.xml
└── README.md
```

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```
   cd my-maven-project
   ```

3. **Build the project**:
   ```
   mvn clean install
   ```

4. **Run the application**:
   ```
   mvn exec:java -Dexec.mainClass="com.leetcode.problem.App"
   ```

## Testing

To run the tests, use the following command:
```
mvn test
```

## Dependencies

This project uses Maven for dependency management. Please refer to the `pom.xml` file for the list of dependencies and plugins used in this project.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.