# Crowd Counting with the Direction of their Movement
###Below is the following methodology I have used:
-Lucas-Kanade method gave me the initial and final vectors of the person.
-The vectors obtained were used to calculate the direction of the subject by the evaluating angle in degrees.
-The video was divided into four quadrants.
  -For North: 135 > theta > 45 , 1st quadrant.
  -For East:   225 > theta > 135 , 2nd quadrant.
  -For South: 315 > theta > 225, 3rd quadrant
  -For West:   360 > theta > 315 or 45 > theta > 0, 4th quadrant
-If the subject is going in a particular direction with theta lying between the any of the given quadrants, it would add to the total count in that direction.
