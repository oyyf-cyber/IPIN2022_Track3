# IPIN2022_Track3

Instructions about the IPIN_Track3 competition:

In terms of how we use the data, our approach consists of two phases: training and testing. In the training stage, the fingerprint is established, the model is trained and some information of the localization environment is extracted. In the test stage, the trained information and the fusion algorithm are used to form the final trajectory.
    In terms of concrete steps, ours method is mainly divided into three modules: relative positioning, absolute positioning and fusion positioning.
    The relative positioning gives the relative displacement of this period of time after the sensor information by the Pedestrian Dead Reckoning.
    Based on Radio Frequency Signals, Geomagnetic, Pressure and other sensor signals, we can calculate the absolute position.We can complete the calculation of absolute position based on the positioning fingerprint data (position information and sensor features) provided by other modules.
    The results of relative positioning and absolute positioning are fused to improve the accuracy of the position.
