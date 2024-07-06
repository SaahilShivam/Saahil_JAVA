SignalDemo

Overview:-
SignalDemo is a Java application that simulates a traffic signal using a graphical user interface (GUI). This program visually represents the operation of traffic lights, switching between red, green, and yellow signals with corresponding messages and timing.

Features:-
Simulates a traffic light with red, green, and yellow signals.
Displays remaining time and action message (Stop, Go, Get Slow) for each signal.
Uses a graphical interface built with Swing components.

Implementation Details:-
GUI Components: Utilizes JPanel for the traffic lights and JLabel for displaying messages.
Threading: Implements the Runnable interface to handle the signal timing and changes in a separate thread.
Colors: Changes the background colors of the JPanel components to simulate the traffic light sequence.
Class and Methods

SignalDemo Class:-
Constructor: Sets up the GUI with traffic light panels and message labels.
run Method: Contains an infinite loop to change the traffic light colors and update the message labels with appropriate delays.
main Method: Creates an instance of SignalDemo, starts the thread to run the simulation.

Usage:-
Clone the repository.
Compile the SignalDemo.java file.
Run the compiled class to start the traffic signal simulation.

Copy code:-
javac SignalDemo.java
java SignalDemo

Dependencies:-
Java Development Kit (JDK)
Swing library (javax.swing)
