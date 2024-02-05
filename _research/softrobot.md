---
title: "Vision-Based Control and Estimation of Soft Robots"
collection: research
type: "Finished project"
permalink: /research/softrobot
venue: "UIUC"
date: 2019-01-01
location: "Champaign-IL"
---
This project investigates the use of vision-based methods to estimate and control a soft robot. The main goal was to use this soft arm for a berry-harvesting robot.

Summary
========
Interest in soft continuum arms (SCAs) has increased as their inherent material elasticity enables safe and adaptive interactions with the environment. 
However, further development in accurate shape sensing and control methods is needed to achieve full autonomy in these arms. 
Vision-based solutions are effective for such tasks. This project investigates the use of vision-based methods to estimate and control a SCA. 
The developed shape estimator utilizes a geometric strain-based representation for the SCA's shape. 
This representation reduces the dimension of the curved shape to a finite set of strain basis functions, 
thereby allowing for efficient optimization for the shape that best fits the observed image. 
Experimental results demonstrate the effectiveness of the proposed approach in estimating the end effector with accuracy less than the soft arm's radius. 
Vision-based control, i.e. Visual Servoing (VS), for SCAs is challenging due to the difficulty in modeling them. Lately, 
more researchers are using the Coserrat Rod Model to accurately model SCAs, since it accounts for the material properties of the SCA and the effect of external forces. 
In this project, a model-based VS method that relies on the Coserrat Rod model is developed. 
A model-free VS method is also developed for cases where the material properties are unavailable. Both eye-in-hand and eye-to-hand VS are demonstrated using these methods. 
Trade-offs arise when deciding to control SCAs with eye-in-hand or eye-to-hand VS. Cameras placed at a distance (eye-to-hand) can observe a larger workspace area and the SCA tip, 
while a camera at the end effector (eye-in-hand) can more accurately survey the target. In this project, a hybrid eye-to-hand and eye-in-hand VS scheme to track a desired object in the SCA's worksapce is introduced. 
When the target is not in the field-of-view of the tip camera, hand-to-eye VS is implemented using a wide field-of-view camera on the soft robot's base, 
to servo the soft robot's tip to a feasible region where the target is expected to be seen by the tip camera. 
This region is estimated by solving an optimization problem that finds the best region to place the SCA, assuming a constant curvature model for the SCA. 
When the tip camera sees the target, the system switches to a hand-in-eye controller that keeps the target in the desired image position of the tip camera. 
Experimental results on the $BR^2$ SCA demonstrate the effectiveness of the hybrid VS scheme under practical settings that include external disturbances.
