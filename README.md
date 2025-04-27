# Elmo_trv_s8 2nd unit
![image](https://github.com/user-attachments/assets/94041915-6e14-4a32-9b15-12efb355ffb1)
This is a  rare S8 film projector with sound. The old low resolution camera has been taken out  
and replaced with the Raspberry Pi HQ camera for real time high resolution capture of video and sound.  
The Raspberry Pi is  small format computer running Linux.  
Once the keyboard and the mouse are attached  and the unit is connected to an HDMI monitor  
 (HDMI cable provided) you are ready to capture your S8 films (sound and no sound)  
 onto internal memory or externally using an HDMI recorder (not provided).  
The recording or previewing process is very simple and does not require any Linux knowledge.  
Just run a few commands    

Sound film:  
record 30000 24 1  
30000 - shutter time in micro seconds  
24 - frame rate  
1 - recorded file sequence number  

Silent film:  
record 30000 18 1  

Run preview:  
Sound film   
preview 30000 24 0  
30000 - shutter  
24 - frame rate  
0 - gain  

Silent film   
preview 30000 18 0  

Sample videos:  
Sound  
https://drive.google.com/file/d/1UM8HyxVCZkZnzBZ71pKxNVG-YHnA6qY4/view?usp=sharing     

Silent
https://youtu.be/N3_q3GoYJBM
