# Steering angle errors caused by two different adversarial examples generated using the Fast Gradient Signed Method (FGSM) (which is a pure digital testing approach) directly printed out and applied in the physical-world case studies.

Figs. 1 and 2 in FGSM.pdf show two testing samples generated using the Fast Gradient Signed Method (FGSM) (which is a pure digital testing approach) directly printed out and applied in the physical-world case studies. As clearly seen, the resulting steering angle error is <5 degree, which is significantly weaker compared to DeepBillboard (>20 degrees in most cases). Thus, directly applying digital perturbation generation methods may not work in physical world settings. Also note that we are not even aware of any existing works trying to apply any digital testing method to do physical-world testing of steering modules. 

Demo.mp4 shows that DeepBillboard is able to continuously deviate a car within each frame. We seek to mimic online testing to evaluate how an actual autonomous vehicle would perform against DeepBillboard. \cb1 In the physical-world evaluation, we tried to pre-record as many abnormally-driving videos as possible to cover a majority of the possible misled driving scenarios of an actual autonomous vehicle. Such videos have been applied in the adversarial construction/training phase.This video shows that \cf4 \cb3 DeepBillboard\cf2 \cb1  is able to continuously deviate a car within each frame. This would mimic one of the many actual autonomous driving scenarios where the vehicle is continuously misled by \cf4 \cb3 DeepBillboard\cf2 \cb1  at each frame(i.e., the misled angle within each frame is similar to the one shown in this video).

If accepted, we would use the additional space to elaborate on these robustness results. The space given in the initial submission was simply too tight for us to include details on such supplementary results.\

<!--
[demo2.mp4](demo2.mp4) shows that DeepBillboard is able to continuously deviate a car within each frame. In the video, at each frame, we control the steering wheel according to the direction of a popular CNN-based steering model, by doing this we simulate the actions of a self-driving vehicle. As seen, the adversarial board can mislead the predicted steering angle to the right. The video was composed of a number of frames and was accelerated by 20 times in order to make it look like a real video. 
 
[error1.pdf](error1.pdf) shows the per-frame steering angle error of the physical study case [case1.jpg](case2.jpg). 

[error2.pdf](error2.pdf) shows the per-frame steering angle error of the physical study case [case2.jpg](case2.jpg).
-->
