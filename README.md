# Sign Up Application Asp.NET

### made by Mojiboye Emmanuel(Dynasty)

### A basic sign up application with database

## Technologies Used
* Git
* Html
* Css
* C#
* Asp.NET Core MVC
* Entity Framework Core
* .NET6 Framework



## Setup/Installation
1. **Clone the Repository**: Open your Git Bash terminal and run the following command to clone the project:
    ```sh
    git clone _REPOSITORY_NAME_
    ```

2. **Install .NET 6.0 Framework**: Ensure you have the .NET 6.0 Framework installed (used .NET 6.0.402 for this application) on your PC. Make sure you have completed the essential steps to write C# code in the REPL.

3. **Create `appSettings.json`**: After cloning the repository, you need to create an `appSettings.json` file in the root directory of the project. Be sure to create it in the production directory of your project (`ToDoList.Solution/ToDoList/appSettings.json`). Use the following template for your `appSettings.json`:

    ```json
    {
        "ConnectionStrings": {
            "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list_with_mysqlconnector;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
        }
    }
    ```

    Replace `[YOUR-USERNAME-HERE]` and `[YOUR-PASSWORD-HERE]` with your actual MySQL username and password.

4. **Build and Run the Application**:
    - To Install all Packages used and Migrations, run the command:
     ```sh
      dotnet restore
      ```

    - If you're not interested in seeing the build messages, run the following command to build and run the application:
      ```sh
      dotnet run
      ```
      This command builds and runs the application for you.

    - If you are interested in seeing the build messages, follow these steps:
        1. **Build the Project**: Run the following command to build the project and add the essential directories to execute the application:
            ```sh
            dotnet build
            ```

        2. **Run the Project**: After building the application, run the following command to see all of the results outputted into the console:
            ```sh
            dotnet run
            ```
        3. **Project in development mode**: If you would love to make changes to the Application, feel free since its licensed under the GNU General Public License. To make changes to app and run app at the same time, use the command:
            ```sh
            dotnet watch run
            ```

## Detected Bugs/ Issues
* No detected bugs

## License 
Licensed under the GNU General Public License

## Contact Info
* _Email: emzzyoluwole@gmail.com_
* _Instagram: @Emmanuel.9944_
* _Twitter: @Emzzy241 and Profile Name: Dynasty_
* _Github Username: Emzzy241_
