# Self_Driving_C3_Scan_Matching_Localization

## ICP Results
From the course introduction we can know the NDT is more accurate than the ICP in most of the situation.But we still spend much to study the ICP method. The ICP is easy to understand, more direct for logical to absorb. It is like the track association in the lidar object detection charpter. 

I took much time on tuning the iterations, filter resolution and scan rate. Finally the iteration =30, the filer resolution = 0.6 and scan rate= 5000, their combination cause the better result. It can achieve the requirement Max.error 1.2m.
![ICP result](https://github.com/junjiexu628/Self_Driving_C3_Scan_Matching_Localization/blob/main/images/project_icp12_iter30_resp65.png)

## NDT Results
