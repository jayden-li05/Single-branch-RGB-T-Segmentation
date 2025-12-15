# Single-branch-RGB-T-Segmentation
The experimental results (predicted masks) and the corresponding weights of our method been uploaded to Google Drive and can be downloaded for free.

[https://drive.google.com/drive/folders/1ehCznXt41-4cbz1IDSCb4CqrteFUcdxv?usp=sharing](https://drive.google.com/drive/folders/1iLjSt-f_eUaYLMIBmMuy17hK_XJ04CvB?usp=sharing)

The four-channel fused dataset used in our work is available at the following link. Alternatively, readers can also obtain it from the original sources of the MFNet or FMB datasets.
https://drive.google.com/drive/folders/16XkqDVFUibgKbS9s8jGd5JdAqgV6U0Zs?usp=sharing

The paper is currently under submission
The code is coming soon.

# MFNet limitation
we further analyzed the MFNet dataset and identified a potential annotation issue. We found that there are 16 ``Guardrail" annotations in the MFNet test set; however, 11 of them are incorrectly labeled as ``Car stop".01234N–01245N.
<img width="2610" height="1498" alt="image" src="https://github.com/user-attachments/assets/9db4d630-6770-4c07-af33-c1a119597e2b" />


