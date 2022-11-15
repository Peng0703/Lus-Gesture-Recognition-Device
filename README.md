# Lu's Gesture Recognition Device
### A Wearable Gesture Recognition System Based on Two-Terminal Electrical Impedance Tomograph (EIT)

This project comes from the following papers:  
>*[1] X. Lu, S. Sun, K. Liu, J. Sun, and L. Xu, “[Development of a Wearable Gesture Recognition System Based on Two-Terminal Electrical Impedance Tomography](https://ieeexplore.ieee.org/document/9626614),” IEEE J. Biomed. Health Inform., vol. 26, no. 6, pp. 2515–2523, Jun. 2022, doi: 10.1109/JBHI.2021.3130374.*  
>*[2] J. Sun, X. Lu, S. Sun, R. Wang, and Y. Xie, “[Application of Multi-channel Impedance Measurement Device in Teaching of ‘Signal Analysis and Processing](https://ieeexplore.ieee.org/document/9534540),’” in 2021 2nd International Conference on Artificial Intelligence and Education (ICAIE), Dali, China, Jun. 2021, pp. 616–620. doi: 10.1109/ICAIE53562.2021.00136.*

Impedance changes during gesture recognition include changes of contact impedance between electrode-skin and changes of internal impedance in the wrist section.

As shown in following figure, network A is the electrode-skin model describing the contact impedance. R_Ele and C_Ele are the resistance and capacitance between the electrode and the surface of conductive glue, respectively, and R_Glu is the resistance produced by the conductive glue. The values of R_Ele, C_Ele and R_Glu depend on the contact state (e.g., different contact areas and pressures) between electrodes and skin. Network B is the basic unit of the impedance network in the wrist section, which describes the impedance characteristics of the biological tissue unit at the specific position. The values of R_Omega and C_Omega depend on the type (e.g., bones, muscle, and blood vessels) and physiological state (e.g., muscle relaxation, contraction, and edema) of the biological tissue unit at that position.

The muscle and skin bulge or twist to varying degrees with different gestures, leading to changes of contact state between electrode-skin and changes of parameters in network A. Besides, gesture changes also cause the movement of biological tissues in the wrist section, resulting in changes of parameters in network B. The changes in the impedance network A&B usually cause the different conductivity distribution in the wrist section, which can be reconstructed by analyzing the impedance changes at the boundary of the wrist section. Thus, different gestures can be recognized by using our EIT system.

![](https://github.com/Peng0703/Lu-s-Gesture-Recognition-Device/blob/main/Pics/principle.png)
