---
layout: page
title: ContextEgoPose
description: Kinematics-Guided Reinforcement Learning for Object-Aware 3D Ego-Pose Estimation
img: /assets/img/projects/contextegopose.gif
importance: 2
type: research
---


<h3 style="text-align: center;font-size:30px"> Kinematics-Guided Reinforcement Learning for Object-Aware 3D Ego-Pose Estimation </h3>
<h4 style="text-align: center;color:DodgerBlue"> Zhengyi Luo, Ryo Hachiuma, Ye Yuan, Shun Iwase, Kris M. Kitani  </h4>
<h5 style="text-align: center;"> arxiv 2020 </h5>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/contextegopose.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<!-- <div class="caption">
    This image can also have a caption. It's like magic.
</div> -->
<br>
<p  align="justify">
    We propose a method for incorporating object interaction and human body dynamics into the task of 3D ego-pose estimation using a head-mounted camera. 
We use a kinematics model of the human body to represent the entire range of human motion, and a dynamics model of the body to interact with objects inside a physics simulator. 
By bringing together object modeling, kinematics modeling, and dynamics modeling in a reinforcement learning (RL) framework, we enable object-aware 3D ego-pose estimation. 
We devise several representational innovations through the design of the state and action space  to incorporate 3D scene context and improve pose estimation quality. We also construct a fine-tuning step to correct the drift and refine the estimated human-object interaction. This is the first work to estimate a physically valid 3D full body interaction sequence with objects (e.g., chairs, boxes, obstacles) from egocentric videos. Experiments with both controlled and in-the-wild settings show that our method can successfully extract an object-conditioned 3D ego-pose sequence that is consistent with the laws of physics.

</p>

<br>


<h3 style="color:darkblue">Demo</h3>

<div class="embed-container">
<center>
  <iframe
      src="https://www.youtube.com/embed/QAK9jTUHRQU"
      width="700"
      height="480"
      frameborder="0"
      allowfullscreen="">
  </iframe>
  </center>
</div>






<br>
<br>
<br>
<h3 style="color:darkblue">Paper and Code</h3>

<div>
{% for paper in site.data.publications.publications %}
    {% if paper.title ==  "Kinematics-Guided Reinforcement Learning for Object-Aware 3D Ego-Pose Estimation" %}
        {% include single_paper.html %}
    {% endif %}
{% endfor %}
</div>

<br>
<br>
<br>
<p> -- </p>