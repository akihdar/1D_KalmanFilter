# 1D_KalmanFilter

Project Name: Predicting Pedestrian position using Kalman Filter.

Team Members: Fidan Aydamirova, Radhika Magaji, Jyothish Babu

College of Science and Engineering,

Seattle University

Problem Statement:

We want to predict the possible future positions of pedestrians. Predicting the motion of a group of pedestrians under vehicle influence is crucial for the development of autonomous vehicle. We want to develop a model that can describe the pedestrian’s motion under the influence of other nearby objects – vehicles and other pedestrians. 

Dataset: 
We are using the dataset collected at two crowded locations in the campus of Dalian University of Technology (DUT) in China.  
The trajectories of pedestrians were already extracted thru processing video frames that come from a down-facing camera mounted on a hovering drone as the recording equipment.
For the sake of simplicity, we are using 1D Kalman filter and considering only the ‘x’ position of one pedestrian.

Github repository details:
1DKalman_Filter_Example.ipynb contains implementation
intersection_01_traj_ped.csv contains raw trajectories of pedestrians. We are using pedestrian with id=1. There are 262 entries for pedestrian with id = 1.

Citations: 
https://paperswithcode.com/paper/top-view-trajectories-a-pedestrian-dataset-of
https://arxiv.org/abs/1902.00487
https://github.com/dongfang-steven-yang/vci-dataset-dut
