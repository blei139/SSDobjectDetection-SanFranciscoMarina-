# SSDobjectDetection-SanFranciscoMarina-
This repository is a SSD object detection project, using the dash camera videoes taken from streets of the Marina District in San Francisco. The object detection algorithm is SSD. The SSD model is 'ssd_mobilnet_v1_coco'. The object detection graph is 'frozen_inference_graph.pb', which has weights baked into the graph as constants and used by tensorflow for object detection. The ipython script, is SSDobjectDetectionVideoProc.ipynb. This script detects objects such stop signs, persons, cars, trucks, bicycles, and traffic lights. This script processes each frame in the input video by detecting objects, using openCV to detect traffic light color specifically for traffic lights. Then, it passes the processed image in each frame into a stream output video with SSD object detection and openCV traffic light color detection.

Instruction to run python script:
At the linux or ubuntu prompt, type this command in the object_detection directory: python SSDobjectDetectionVideoProc.py .

See my youtube video here: 
https://youtu.be/wfEa3KpEjbo
