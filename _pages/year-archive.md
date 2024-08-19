---
layout: archive
permalink: /year-archive/
title: "Blog posts"
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

Updates about recent works
======
On the current page, some additional explanations about my recent works (including articles and thesis) are mentioned.

Chisel bits cutting force estimation using XGBoost and different optimization algorithms
==
![Untitled-1](https://github.com/user-attachments/assets/529c8bb0-2315-4c69-b95a-1eaec3ff9089)

**Abstract**

The design and selection of tools for mechanized excavations is a crucial topic in the field of tunneling. Chisel bits are commonly used tools for soft ground, with the required cutting force being a vital factor in tool design. However, current methods either lack accuracy or fail to consider all necessary parameters. To address this issue, a new cutting force prediction model was developed to improve response quality and consider the most effective parameters. 206 data points were collected from studies on rock cutting with different strength, including information such as Uniaxial compressive strength, Brazilian tensile strength, Depth, Width, Rake angle, and clearance angle. Five different algorithms were then used to optimize the Hyperparameters in the XGBoost method, including Grid Search, Random Search, Bayesian Algorithm, Differential Evolution, and Optuna. Results showed that while most algorithms provided appropriate responses, the Grid Search and Bayesian Algorithm methods were the most effective, with R2 values (in test and train) of 0.876 and 0.93 in GS and 0.872 and 0.926 in BO, respectively. Upon comparison of the two methods, it was discovered that the GS approach yields a superior solution; however, it is also more sensitive to tuning, requires more calculations, and takes longer to provide a solution. When assessing the newly presented approach against existing methods, it was noted that the Evans and Roxborough methods produced R2 values of 0.48 and 0.53, respectively, which are notably lower than those of the new method. Lastly, the parametric analysis revealed that the cutting force is primarily affected by the depth, width, and rake angle in that order.

MSc Thesis: Comparative study of the results of existing models and numerical modeling for the forces applied to conventional TBM cutting tools on soft grounds
==
![vid03](https://github.com/user-attachments/assets/1dd20215-132a-48d2-a882-d898b3682675)

**Abstract**

Over the years, and by increasing the demand for building mechanized tunnels, designing the Tunnel Boring Machines (TBM) become increasingly sensitive. Engineers and scientists are increasingly interested in optimizing the layout of cutterheads to reduce investment and maintenance expenses. One of the vital factors for this purpose is the geometry of the dragbit. In other words, by optimizing the geometry parameters of dragbits, it is possible to lower investment and maintenance costs. On the other hand, cutting force is declared the most important factor affected by dragbits geometry and rocks strengthen parameters. The first step of this study is to review the current methods used for estimating the cutting force. Secondly, numerical models were made to investigate the effect of each parameter on the cutting force. In the very next step, a comparison study was done between the results of the numerical models' cutting force and the existing forces. Thus, Rake angle, Clearance angle, width, bezel width, attack angle, and tilt angle were studied in this thesis. The results show that the cutting force is reduced by increasing the rake, clearance, attack, and tilt angles; However, the cutting force registered a significant increase when the width and bezel width are increased. Compared to the previous models, it was observed that although these methods can take into account the changes in the width, rake, and clearance angles, they are not able to show the sensitivity of force to other geometric parameters. In addition, the supplementary research indicates that the Evans, Nishimatsu, and CEIT models provided similar results to the numerical models in rock. The tear and shear types showed noteworthy outcomes compared to the numerical model.

