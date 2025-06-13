# Wearable Haptic Device for Individuals with Congenital Absence of Proprioception
Code for NIH Intramural project with RTW for developing a sensory substitution device for individuals with congenital absence of proprioception

for running demo:

in TestA.py, change ip address to your wifi connection's ip address.
Then run JNDtestBLEV2.py, name a subject number. This will create a timestamped directory.
Then run TestA.py. It will seek your newly created folder.
This GUI will need access to a GIF-format image: "keypadJND.gif". This is accessed in line 168 of "skBLESupport_JND.py" (change path if you locally downloaded this image). If the images are buggy, comment out things saying "shape" (eg. "tr.shape") in skBLESupport script. There should be 9 total. 
