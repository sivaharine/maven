The Maven Home Page Project is a simple Java Swing GUI application that serves as a homepage with multiple navigable pages.
It is built using Java AWT & Swing and managed with Maven for dependency management and build automation. 
The application consists of a main home screen displaying a welcome message and buttons for navigating to additional pages such as "About," "Settings," and "Contact Us."
The project structure follows the Maven standard directory layout, ensuring modularity and scalability.
Maven helps streamline the build process, manage dependencies, and facilitate execution using the exec-maven-plugin. 
The project can be packaged as a JAR file and executed directly through the command line.

1️⃣ Clean and Build the Project
This removes old build files and compiles the project:

mvn clean package

2️⃣ Run the Application Using Maven
Execute the main class using the Maven exec plugin:

mvn exec:java -Dexec.mainClass="com.example.HomePage"

