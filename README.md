# Ware-House
This project demonstrates an automated warehouse system that uses a robotic arm and conveyor belt to move boxes from storage shelves to a processing area. The system is designed to operate continuously, improving warehouse efficiency and reducing manual labor.

## Components
- **Robotic Arm**: Picks and places boxes from shelves to the conveyor.
- **Conveyor Belt**: Transports the boxes to the next station.
- **Storage Shelves**: Organized layout of boxes for automated pickup.
- **Gripper**: Attached to the robotic arm for handling boxes.
- **Sensors**: Used for detecting box position, confirmation of grip, and placement.

## Execution Algorithm
The system operates in a continuous loop following these main steps:

1. **Initialization**: Activate all system parts including the robot arm and conveyor belt.
2. **Detection**: Identify which boxes are available on the shelf for pickup.
3. **Positioning**: Calculate and move to the box's exact location using 3D coordinates.
4. **Pickup**: Engage the gripper to lift the box safely from the shelf.
5. **Transfer**: Rotate and extend the arm toward the conveyor system.
6. **Placement**: Release the box precisely onto the conveyor belt.
7. **Transport**: Conveyor moves the box to the next processing area.
8. **Repeat**: Loop continues until all boxes have been handled.
9. **Shutdown**: The system stops or waits for new input once the task is complete.

## Usage
1. Load the 3D model in a simulation environment (e.g., Tinkercad, Unity, or a custom simulator).
2. Initialize the system.
3. Begin execution and observe automated handling of boxes.
4. Monitor performance and status through sensor feedback.
