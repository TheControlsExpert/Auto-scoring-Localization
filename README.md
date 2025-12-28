## Auto-scoring-Localization

# Auto-scoring algorithm 
Can be found in src/main/java/frc/robot/Commands/AutoAlignReef/

First part of path is in FirstPartAutoAlign.java, second part of the path is in SecondPartAutoAlign.java, moving backwards is in ThirdPartAutoAlign.java
The whole sequence is stored in AutoAlignReef.java

# Localization

Wheel odometry, sensor fusion, and collision/roll/pitch calculation for deciding when to disable april tag distance filtering is found in src/main/java/frc/robot/Subsystems/Drive/Drive.java in the periodic() method

Vision measurements are received, sorted, and sent to Drive.java in the src/main/java/frc/robot/Subsystems/Vision/VisionSubsystem.java file




