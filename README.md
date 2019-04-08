<html>
<body>

<h1>Detect shadow region from an image <br> applying Grad-cam to binary shadow classifier CNNs</h1>
<h2>Background</h2>
<div>
<p>Generally, outdoor object are influenced by various optical phenomenons.
For instance, reflection of lights and shadows.
Those phenomenons makes edge and blobs and finally,they causes object appearance changes.
And, because of the object appearance changes effects a serious negative influence in outdoor object classifier CNNs,
      There are some needs to detecting shadow and removal from image.<br>
      So, this time, we suggest computional low-cost shadow detecter using Grad-CAM.
      By optimizing Grad-CMA to binary classifier Convolutional Neural Network which classifies shadow containing image, we believe it makes significant computional cost reduction. 
</p>
</div>
    
<h2>Shadow Detecter Architecture</h2>
<div>
<img alt="er" src="https://github.com/Eljefemasao/Graduation_Research/blob/development/images_for_readme/binary.png" >
</div>


<h2>Result on actual outdoor object </h2>

<div>
<img alt="er" src="https://github.com/Eljefemasao/Graduation_Research/blob/development/images_for_readme/gradcam.png" >
</div>


<h2>Major Dependencies</h2>
<ul>
<li>python:3.6.3</li>
<li>tensorboard:1.11.0</li>
<li>tensorflow-gpu:1.11.0</li>
<li>scikit-learn:0.19.1</li>
<li>keras:2.1.3</li>

</ul>
<h2>Files/Directories</h2>
<ul>
<li>classify_seesa_keras.ipynb: main code</li>
</ul>

</body>
</html>
