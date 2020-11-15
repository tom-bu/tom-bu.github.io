---
layout: page
title: Stress Analysis Through Twitter
description: "The rural–urban stress divide: Obtaining geographical insights through Twitter"
img: /assets/img/projects/tweet.png
importance: 4
type: research
---

<h3 style="text-align: center;font-size:30px"> The rural–urban stress divide: Obtaining geographical insights through Twitter </h3>
<h4 style="text-align: center;color:DodgerBlue"> Kokil Jaidka, Sharath Chandra Guntuku, Jane H Lee, Zhengyi Luo, Anneke Buffone, Lyle H Ungar  </h4>
<h5 style="text-align: center;"> Computers in Human Behavior, 2020 </h5>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/twitter/all_pos.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<!-- <div class="caption">
    This image can also have a caption. It's like magic.
</div> -->
<br>
<p  align="justify">
    To understand rural–urban differences in stressors, this study compared the cognitive and emotional language in geolocated Twitter posts in the United States against survey-reported county-level trends from the Gallup-Sharecare Well-Being Index. Mentions of stress on Twitter can predict population-level trends in stress in both rural (R2=31.6%) and urban (R2=26.7%) communities. While mentions of poor health are limited to only rural areas with low socioeconomic status, higher emotional expression is associated with higher stress across all rural communities. Controlling for socioeconomic status, urban communities reporting higher stress are also more likely to discuss relationships on Twitter. The findings contribute to an understanding of how language use on social media acts as a barometer of the social and cultural differences between regions.

</p>

<br>

<br>
<br>
<br>
<h3 style="color:darkblue">Paper and Code</h3>

<div>
{% for paper in site.data.publications.publications %}
    {% if paper.title ==  "The rural–urban stress divide: Obtaining geographical insights through Twitter" %}
        {% include single_paper.html %}
    {% endif %}
{% endfor %}
</div>

<br>
<br>
<br>
<p> -- </p>