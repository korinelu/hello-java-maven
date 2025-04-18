# HelloJavaMaven - Jenkins + Maven Build Example

This project demonstrates how to build a simple **Java HelloWorld application** using **Maven** and **Jenkins**.

## Prerequisites

Make sure you have the following installed:

- **Java 17** (or compatible version)
- **Maven**
- **Jenkins** (for CI/CD automation)

## Project Structure

hello-java-maven/ ├── src/ │ └── main/ │ └── java/ │ └── HelloWorld.java ├── pom.xml └── README.md



### File Descriptions:
- **`src/main/java/HelloWorld.java`**: Prints "Hello, Jenkins + Maven!".
- **`pom.xml`**: Maven build configuration.
- **`README.md`**: Project documentation.

## How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/hello-java-maven.git
   cd hello-java-maven
Build the app using Maven:


mvn clean package
Run the application:


java -jar target/hello-1.0.jar
You should see:


Hello, Jenkins + Maven!
Jenkins CI/CD Setup
1. Create a Jenkins Job
Create a Freestyle Project.

Under Source Code Management, select Git and add the repo URL:


https://github.com/<your-username>/hello-java-maven.git
Add a Build Step to run Maven:

Goal: clean package

2. Build the Project
Click Build Now and check the Console Output for BUILD SUCCESS.

Conclusion
This project demonstrates building a Java app using Maven and automating the build process with Jenkins.



---

### Key Points to Include:
- **Project Overview**: A brief description of what the project does.
- **Installation & Running Instructions**: How to clone, build, and run the app locally.
- **Jenkins CI/CD Setup**: Basic steps to set up Jenkins and run the build.
- **Output**: Example of what the user should see.

---

This version is more concise and focuses on the essential steps for your assignment. Let me know 
