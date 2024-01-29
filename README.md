# UnifiedSense Dataset
This repository contains the dataset used in the paper titled *"UnifiedSense: Enabling Without-Device Gesture Interactions Using Over-the-shoulder Training Between Redundant Wearable Sensors"*, published in *Proceedings of the ACM on Human-Computer Interaction 7 (MHCI)*.
https://dl.acm.org/doi/abs/10.1145/3604277

## Citation
If you've used this in your research or project, consider citing the associated paper:
```
@article{10.1145/3604277,
	author = {Azim, Md Aashikur Rahman and Rahman, Adil and Heo, Seongkook},
	title = {UnifiedSense: Enabling Without-Device Gesture Interactions Using Over-the-shoulder Training Between Redundant Wearable Sensors},
	year = {2023},
	issue_date = {September 2023},
	publisher = {Association for Computing Machinery},
	address = {New York, NY, USA},
	volume = {7},
	number = {MHCI},
	url = {https://doi.org/10.1145/3604277},
	doi = {10.1145/3604277},
	abstract = {Wearable devices allow quick and convenient interactions for controlling mobile computers. However, these interactions are often device-dependent, and users cannot control devices in a way they are familiar with if they do not wear the same wearable device. This paper proposes a new method, UnifiedSense, to enable device-dependent gestures even when the device that detects such gestures is missing by utilizing sensors on other wearable devices. UnifiedSense achieves this without explicit gesture training for different devices, by training its recognition model while users naturally perform gestures. The recognizer uses the gestures detected on the primary device (i.e., a device that reliably detects gestures) as labels for training samples and collects sensor data from all other available devices on the user. We conducted a technical evaluation with data collected from 15 participants with four types of wearable devices. It showed that UnifiedSense could correctly recognize 5 gestures (5 gestures \texttimes{} 5 configurations) with an accuracy of 90.9\% (SD = 1.9\%) without the primary device present.},
	journal = {Proc. ACM Hum.-Comput. Interact.},
	month = {sep},
	articleno = {230},
	numpages = {25},
	keywords = {over-the-shoulder training, unified gesture interactions, wearables}
}
```
