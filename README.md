# Calculator
# Downloading and Running a Java Application

## Step 1: Downloading the Repository

1. Go to the [GitHub repository](https://github.com/Unintellectual/Calculator).
2. Click on the green "Code" button on the right side of the page.

    - **Download ZIP**: Click on "Download ZIP" to download the repository as a compressed ZIP file. Once downloaded, extract the contents to a folder on your computer.

    - **Using Git (recommended)**: If you have Git installed on your system, you can clone the repository using the following command:

      ```
      git clone https://github.com/Unintellectual/Calculator.git
      ```

## Step 2: Compiling and Running the Application

1. **Install Java Development Kit (JDK)**:

    - If you don't have the JDK installed, you can download it from the official [Oracle website](https://www.oracle.com/java/technologies/javase-downloads.html) or from an alternative source like OpenJDK.

2. **Open a Terminal/Command Prompt**:

    - Navigate to the directory where you extracted the ZIP file or cloned the repository using the `cd` command. For example:

      ```
      cd /path/to/Calculator
      ```

3. **Compile the Java Code**:

    - Find the Java source files (`.java` files) in the repository. There might be a main class (typically with a `public static void main(String[] args)` method) that you need to run.

    - Compile the Java code using the `javac` command followed by the name of the main Java file. For example:

      ```
      javac Main.java
      ```

      This will generate the corresponding `.class` files.

4. **Run the Application**:

    - Once the code is compiled successfully, you can run the application using the `java` command followed by the name of the main class (without the file extension). For example:

      ```
      java Main
      ```

      This command should start the calculator application.

### Additional Notes:

- Make sure that the repository contains a Java source
