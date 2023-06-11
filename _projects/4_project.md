---
layout: page
title: Diabetes Classification Using ML
description: Predict whether or not a patient has diabetes <br> May 2022 – Sept. 2022
img: assets/img/cse422_0.jpg
redirect: 
importance: 4
category: Academic
---
It is a simple Machine Learning project where I tried to classify if a person has Diabetes or not. I collected the dataset from Kaggle.

<a href="https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database">Dataset Link</a>

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. 

After pre-processing the dataset, I splitted the dataset into 75:25 ratio. 75% data for training and 25% data for testing.  

I used three classification models:
- Decision tree
- Random Forest 
- K-neighbors classifier


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_1.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Correlation Heatmap
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_2.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_3.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_4.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Confusion Matrix
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_5.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_6.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse422_7.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Results
</div>

You can find more about the project <a href="https://github.com/kazimdalwakil/Diabetic-Classification---CSE422-ML-Project">here.</a>
