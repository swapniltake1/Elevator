# Elevator (Task 1 - YHills Java Training)

Q. Design and code an Elevator. You can use any JDK, preferably JDK 8 and use collection framework, OOP principles to design a single 
thread elevator programme. This will test your knowledge of CORE Java. Remember to use all the standard and good programming habits 
while programming.

# Flow Of Code

1. The Elevator class maintains the current floor, direction of movement, a map of requested paths (people waiting on each floor and their destinations), and an array to track the floors the elevator will visit.

2. The start() method repeatedly calls the processFloor() method until the elevator becomes idle.

3. The processFloor() method unloads passengers, boards passengers, updates the current floor destinations, and calls moveElevator() to determine the next direction and move the elevator.

4. The moveElevator() method determines the direction based on the current floor and updates the currentDirection variable accordingly.

5. The elevator moves up or down based on the current direction and waits between each floor.

6. The callElevator() method adds user requests to the requestedPathsMap.

7. The main method creates an Elevator object, allows users to manually call the elevator, and starts the elevator.

# Output Screenshot 

![image](https://github.com/swapniltake1/Elevator/assets/61576958/2acd59cb-1400-416b-a102-a9c6e1cdde00)

