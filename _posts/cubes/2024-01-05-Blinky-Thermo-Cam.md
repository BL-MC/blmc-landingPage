---
layout: page-fullwidth
subheadline: "Instrumentation"
title:  "Blinky-Thermo-Cam "
teaser: "with JupyterLab integration for deep learning"
breadcrumb: true
tags:
    - post instrumentation
categories:
    - cubes
image:
    thumb: 2024-01-05/2024-01-05-01_thumb.jpg
header: no
---
Since the Blinky-Lite framework uses [MongoDB](https://www.mongodb.com/) for storing data, integration into [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/) using [PyMongo](https://pymongo.readthedocs.io/en/stable/) is straightforward. As an example, we integrated the [Blinky-Thermo-Cam](https://github.com/Blinky-Lite/blinky-thermo-cam-cube) with JupyterLab. This integration could be used to <span style="color:#ff6100;font-weight: bold"> develop deep-learning models</span> for thermal imaging streams which could be useful in many diverse  fields such as <span style="color:cyan;font-weight: bold">animal monitoring, chemical process monitoring, or equipment failure diagnosis</span>. 

Blinky-Thermo-Cam is a low cost, remotely deployable, thermal imaging processing system based on the [Flir Lepton LWIR Micro Thermal Camera Module](https://www.flir.com/products/lepton/?vertical=microcam&segment=oem). Blinky-Thermo-Cam is wireless and can operate on 5V batteries for remote operation. Periodic, manual, or motion triggering modes are available.

<div class="row t30">
    <div class="medium-6 columns">
        <a href="{{ site.urlimg }}/2024-01-05/2024-01-05-02.jpg"><img src="{{ site.urlimg }}/2024-01-05/2024-01-05-02.jpg" ></a>
    </div>

    <div class="medium-6 columns" >
        <div style="position: relative; padding-bottom: 75%;height: 0px;">
            <iframe style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%;" frameborder="0" allowfullscreen="" src="https://player.vimeo.com/video/906812643?dnt=1"></iframe>
        </div>
    </div>
</div>
<div class="row t30">
    <div class="medium-4 columns">
         <a href="{{ site.urlimg }}/2024-01-05/2024-01-05-03.jpg"><img src="{{ site.urlimg }}/2024-01-05/2024-01-05-03.jpg" ></a>
    </div>
    <div class="medium-4 columns">
         <a href="{{ site.urlimg }}/2024-01-05/2024-01-05-05.png"><img src="{{ site.urlimg }}/2024-01-05/2024-01-05-05.png" ></a>
    </div>
    <div class="medium-4 columns">
         <a href="{{ site.urlimg }}/2024-01-05/2024-01-05-04.jpg"><img src="{{ site.urlimg }}/2024-01-05/2024-01-05-04.jpg" ></a>
    </div>
</div>
