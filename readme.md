# Steering angle errors caused by two different adversarial examples generated using the Fast Gradient Signed Method (FGSM) (which is a pure digital testing approach) directly printed out and applied in the physical-world case studies.

[demo2.mp4](demo2.mp4) shows that DeepBillboard is able to continuously deviate a car within each frame. In the video, at each frame, we control the steering wheel according to the direction of a popular CNN-based steering model, by doing this we simulate the actions of a self-driving vehicle. As seen, the adversarial board can mislead the predicted steering angle to the right. The video was composed of a number of frames and was accelerated by 20 times in order to make it look like a real video. 
 
[error1.pdf](error1.pdf) shows the per-frame steering angle error of the physical study case [case1.jpg](case2.jpg). 

[error2.pdf](error2.pdf) shows the per-frame steering angle error of the physical study case [case2.jpg](case2.jpg).
