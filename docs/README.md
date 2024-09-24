To set up this C# project on your local machine, ensure that the system requirements are met, and then follow these instructions:

<h3>System Requirements</h3>

- **.NET SDK:** Version 8 or later ([Download .NET](https://dotnet.microsoft.com/en-us/download)).

- **Operating System:** Windows, macOS, or Linux.

<h3>Steps to Install</h3>

1. **Clone or Download the Project**

    - **Clone the Repository**
    
      Use Git to create a local copy by executing the following command:

      ```bash
      git clone {{REPOSITORY_URL}}.git
      ```

    - **Download as ZIP**

      If Git is not available, you can download the project as a ZIP file from the GitHub repository by clicking the “Code” button and selecting the “Download ZIP" option.

2. **Navigate to the Project Directory**

    Navigate to the project directory containing the source files by executing the following command:

    ```bash
    cd {{REPOSITORY_NAME}}/src
    ```

    > **Note:** Make sure you're in the correct parent directory where the `{{REPOSITORY_NAME}}` folder is located.
    
3. **Restore Dependencies**

    Install all required packages and libraries by executing the following command:

    ```bash
    dotnet restore
    ```

    This command uses NuGet to download and install the dependencies specified in the project’s configuration files.

<h2 id="usage">🧑‍💻 Usage</h2>

To run the console application, there's serval options can be use:

1. From Visual Studio
    - Press Ctrl + F5 to run without debugging.

    - Press F5 or click the green start button to run with debugging.
    
2. From .NET CLI

    ```bash
     dotnet run
     ```
