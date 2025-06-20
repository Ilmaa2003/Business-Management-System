# Project Setup Instructions

## Prerequisites

![Business Management System Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Business-Management-System/main/Extra/Images/Screenshot%202024-11-13%20191410.png)

![Business Management System Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Business-Management-System/main/Extra/Images/Screenshot%202024-11-13%20185157.png)

![Business Management System Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Business-Management-System/main/Extra/Images/Screenshot%202024-11-13%20182306.png)


- **Windows OS** (recommended for compatibility)
- **Visual Studio** (for C# development)  
  Download: [https://visualstudio.microsoft.com/downloads/](https://visualstudio.microsoft.com/downloads/)
- **SQL Server Management Studio (SSMS)** (for database management)  
  Download: [https://aka.ms/ssms](https://aka.ms/ssms)
- **Crystal Reports Runtime** (for report generation)  
  Download: [https://www.sap.com/cmp/td/sap-crystal-reports-visual-studio-trial.html](https://www.sap.com/cmp/td/sap-crystal-reports-visual-studio-trial.html)

## Installation Steps

1. **Clone or Download the Project**  
   Download the source code and open the solution (`.sln`) file in Visual Studio.

2. **Restore NuGet Packages**  
   In Visual Studio, restore any missing NuGet packages via **Tools → NuGet Package Manager → Manage NuGet Packages for Solution**.

3. **Set up the Database**  
   - Open SQL Server Management Studio.  
   - Create a new database or restore the provided database backup (`.bak`) if available.  
   - Execute the provided SQL scripts (if any) to create tables and seed initial data.

4. **Configure Database Connection**  
   - Open the project's configuration file (`App.config` or `Settings`).  
   - Update the connection string to point to your local SQL Server instance and database.

5. **Install Crystal Reports Runtime**  
   Ensure Crystal Reports runtime is installed on your machine for report generation.

6. **Build and Run the Application**  
   - Build the solution in Visual Studio (**Build → Build Solution**).  
   - Run the application (**Debug → Start Debugging** or press `F5`).

## Notes

- Ensure SQL Server service is running before launching the application.  
- Crystal Reports runtime and Visual Studio integration must be correctly installed for report generation.

---

If you encounter any issues, please refer to the detailed project report or contact the project maintainer.
