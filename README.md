📖 Project Description
This is a simple Employee Task Tracker built using:

Java
Maven
H2 In-Memory Database
Spring JDBC
Repository → Service → Console UI Layers
JUnit 5 Tests

Features:

Add a task
View tasks
Mark task as completed
Delete a task
Automatic H2 table creation
Clean architecture

▶️ How to Run the Program
1. Build Project
mvn clean install

2. Run Application
java -cp target/task-tracker-1.0-SNAPSHOT.jar com.tasktracker.Main

OR from IntelliJ:

Right–click Main.java
Click Run


📝 Sample Input & Output
Add Task
====== MENU ======
1. Add Task
Enter choice: 1
Title: Work
Description: Complete assignments
Task added!

View Tasks
---- Tasks ----
1 | Work | PENDING

Mark Task Complete
Enter choice: 3
Task ID to complete: 1
Task Completed!

Delete Task
Enter choice: 4
Task ID to delete: 1
Task Deleted!


🧪 JUnit Tests
Tests cover:

Adding a task
Completing a task

Run:
mvn test
