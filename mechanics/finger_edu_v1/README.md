# FingerEdu v1

<img src="images/finger_edu_1.jpg" width="300"> <br>
*Finger module assembled. Weight: 930g*<br>  
<img src="images/finger_edu_2.jpg" width="400"> <br>
*The finger can be completely retracted into the base structure for  transport.*<br>  

## Actuator Modules
<img src="images/finger_actuator_modules_1.jpg" width="400"> <br>
*Each finger consists of 3 different actuator modules*<br>  

For the finger we are using the same actuator modules that are used for the 12dof quadruped. There is more detailed information [here](../leg_3dof_v1).
* Hip AA actuator module - 148g
* Hip FE actuator module - 160g
* Upper Leg actuator module - 155g

## Finger Base Frame
<img src="images/finger_base_frame_1.jpg" width="400"> <br>
*Assembled base frame - weight: 226g*<br>

The STL files for 3d printing the shells of the 3dof leg can be found here: [STL files finger base frame](stl_files).

## Finger Link
<img src="images/finger_tip_1.jpg" width="400"><br>*Finger link with finger tip - weight: 22g*

The finger link was printed on a FDM printer with the setting: "sparse double dense".  
The STL file for 3d printing the finger link can be found here: [STL files finger link](stl_files).

<img src="images/finger_tip_2.jpg" width="300"> <br>*Rubber finger tip - weight 2g*<br>
* we ordered the rubber finger tip from Amazon
* it's a standard office product for handling paper
* look for "Rubber Thimblette" - size 2 - large

## Electronics
<img src="images/finger_electronics_stack_1.jpg" width="500"> <br>*Dual Texas Instruments motor driver stack*<br>

Since space and weight isn't a concern here we are using the [Texas Instruments evaluation motor driver electronics](../../electronics/ti_electronics/README.md).<br>
Each finger module requires 24V power supply and 2 CAN communication channels.

-------------
## Authors
Felix Grimminger

## License
BSD 3-Clause License

## Copyright
Copyright (c) 2019-2020, Max Planck Gesellschaft and New York University

## More Information
[Open Dynamic Robot Initiative - Webpage](https://open-dynamic-robot-initiative.github.io)  
[Open Dynamic Robot Initiative - YouTube Channel](https://www.youtube.com/channel/UCx32JW2oIrax47Gjq8zNI-w)   
[Open Dynamic Robot Initiative - Forum](https://odri.discourse.group/categories)  
[Open Dynamic Robot Initiative - Paper](https://arxiv.org/pdf/1910.00093.pdf)  
[Hardware Overview](../../README.md#open-robot-actuator-hardware)  
[Software Overview](https://github.com/open-dynamic-robot-initiative/open-dynamic-robot-initiative.github.io/wiki)
