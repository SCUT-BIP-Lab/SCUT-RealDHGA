# SCUT-RealDHGA
SCUT-RealDHGA: A Real-world Database for Dynamic Hand Gesture Authentication

## Short Information
SCUT-RealDHGA Database is used for scientific research of dynamic hand gesture authentication. It is collected by the BIP Lab, School of Automation Science and Engineering, South China University of Technology (SCUT). Any one or group is allowed to use this database free of charge.

SCUT-RealDHGA Database is collected at various practical scenarios, including dormitories, classrooms, laboratories, and subway stations. It contains realistic and diverse backgrounds, illumination, and viewpoints; therefore, it is suitable for evaluating the robustness of the DHGA algorithm. This dataset contains 60 IDs right now, and is growing with time. For each identity, we collect 10 gesture types, including defined gesture and random gesture.

![SCUT-RealDHGA](https://github.com/SCUT-BIP-Lab/SCUT-RealDHGA/blob/main/images/realdhga.png)

## File Naming Convention
Images are labeled as follows: 
train/test_session_ID_gesture_sample, where "train/test" indicates whether the video sample belongs to the training set or the testing set,
"session" stands for session number, which is "1" in this dataset,
"ID" stands for the client's ID,
"gesture" ranges from 0 to 9, standing for ten gesture types,
"sample" stands for the repetitions of the sample, ranging from 0 to 5,
The naming convention of SCUT-RealDHGA is the same as the SCUT-DHGA database. Please refer to https://github.com/SCUT-BIP-Lab/SCUT-DHGA for details.

## Request
The SCUT-RealDHGA is publicly available (free of charge) to the research community (after the paper is published).  
Unfortunately, due to privacy reasons, we cannot provide the database for commercial use. 

Those interested in obtaining SCUT-RealDHGA should download [release agreement](https://github.com/BIP-Lab/SCUT-RealDHGA/blob/master/SCUT%20FV%20Presentation%20Attack%20Database%20Release%20Agreement.pdf), and send by email one signed and scanned copy to scutbip@outlook.com.

<!-- While reporting results using the SCUT-RealDHGA, please cite the following article:  
@ARTICLE{10654331,
  author={Zhang, Yufeng and Kang, Wenxiong and Song, Wenwei},
  journal={IEEE Transactions on Information Forensics and Security}, 
  title={Robust and Accurate Hand Gesture Authentication With Cross-Modality Local-Global Behavior Analysis}, 
  year={2024},
  volume={19},
  number={},
  pages={8630-8643},
  keywords={Authentication;Videos;Feature extraction;Physiology;Robustness;Lighting;Spatiotemporal phenomena;Biometrics;hand gesture authentication;multimodal fusion;spatiotemporal analysis;behavioral characteristic representation},
  doi={10.1109/TIFS.2024.3451367}} -->


## Contact
Zhang Yufeng
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
auyfzhang@mail.scut.edu.cn

Wang Xilai
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
auwangxilai@mail.scut.edu.cn

Prof. Kang Wenxiong  
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
auwxkang@scut.edu.cn
