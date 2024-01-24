C1 - ring2glass
C2 - ring2headphone
C3 - ring2watch
C4 - watch2headphone
C5 - watch2glass

1. Use *labels.txt* for all cases. They are cleaned labels. *labels - Copy.txt* contains the labels where misdetection happeded from the reliable wearables (e.g., the participants performed tap on smartgalls but it detcted as swipes)
2. For all cases: gesture_type: 0 - tap, 1 - swipe right, 2 - swipe left, 3 - swipe up, 4 - swipe down
3. gesture_trial_number is not required for segmentation

# C1 & C5
*labels.txt* in ring2glass, watch2glass
timestamp, gesture_trial_number, gesture_type


# C2, C3, C4
timestamp_start: trigger start from the gesture
timestamp_end: trigger end from the gesture

==> this actually refers to when swipe start and when swipe ends.
==> I used timestamp_end for segmentation

*labels.txt* in ring2headphone, ring2watch, watch2headphone
gesture_trial_number, gesture_type, timestamp_start, timestamp_end 


# for all three files: glassSensor1.txt, ringSensor1.txt, watchSensor1.txt
timestamp, device_id, acc_x, acc_y, acc_z, qw, qx, qy, qz

device_id: 1 - watch, 2 - ring, 3 - glassSensor1
3-axes acceleration: (acc_x, acc_y, acc_z)
quaternion (4-tuples): qw, qx, qy, qz




