# AMAZON-Go-To-Goal-
AIM

To compute the Euclidean distance between the robot’s current position and the goal.

PROCEDURE
Initialize start and goal coordinates
Apply the distance formula
Substitute the given values
Compute the distance
Display the result
CODE
import math

# Coordinates
x1, y1 = 0, 0
x2, y2 = 6, 8

# Distance calculation
distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

# Output
print("Distance:", distance, "m")
OUTPUT

Distance: 10 m

RESULT

The Euclidean distance between the start and goal positions is 10 m, representing the shortest path for navigation.
