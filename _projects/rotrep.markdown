---
layout: page
title: Rotation Representaiton
description: Rotation Representations in Deep Learning
img: /assets/img/projects/rotrep/rotrep.png
importance: 3
type: class
---



<h3 style="text-align: center;font-size:30px"> Rotation Representations in Deep Learning </h3>
<p  align="center">
<a  style="color:darkblue;font-size:1.2vw" href="../../assets/pdf/Rotation_DL.pdf">[Report]</a>
</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0" align="center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/rotrep/rotrep_teaser.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<br>
<p  align="justify">
    In this project, we reviewed several popular rotation representations, discussed their discontinuitiesand  other  problems  in  a  direct  regression  task.   Different  from  previous works,  we  focused  on  giving  an  intuitionon why those representations are discontinuous and their respective properties in a regression task.  Totest our hypothesis empirically, we generated a dataset based on ShapeNetV1 3D model dataset anddesigned experiments on 3D rotation estimation task using CNN as model and images as input.  We triedseveral traditional rotation representations as well as the 6DOF rotation representation proposed in and we found that 3D and 4D rotation representations indeed yield larger training and testing errorsdue to their discontinuity, while rotation matrix works better and the 6DOF representation works bestin the 3D rotation pose estimation task.

</p>

[This is my final project for 16-811: Math Fundamentals for Robotics at CMU]




