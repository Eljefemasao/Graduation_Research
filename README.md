<html>
<body>
  <h1>Introduction of my Graduation Research</h1>
By conducting command which is described bottom, you can check my main code used at Graduation Research.
  
  <div>
    ```
    jupyter notebook classify_seesa_keras.ipynb

    ```
    </div>
<h2>Detect shadow region from an image <br> applying Grad_CAM to binary shadow classifier CNN</h2>
<h2>Research Background</h2>
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

<h2>What is Grad_CAM</h2>
<div>
 Gradient-weighted Class Activation Mapping(Grad-CAM)is an excellent visualization idea for understanding Convolutional Neural Network functions. As more detail explanation of this technique, It uses the gradients of any target concept(say logits for 'dog' or even a caption),flowing into the final convolutional layer to produce a coarse localization map highlighting important regions in an image for predicting the concept.
Furthermore, By piling up these localization map onto Guided Backpropagation output, it realizes high level visualization system.
  There are roughly two algorithm flows. One is the Class Activation Mapping(CAM) and the other one is Guided BackPropagation.
  CAM is one of the funduamental idea for Grad-CAM. 
</div>
<h2>Shadow Detecter Architecture</h2>

<div>
  Our new idea is to highlighting shadow region in an input image pixel by optimizing Grad-CAM idea.
  As shown bottom diagram,
</div>
<div>  
<img alt="er" src="https://github.com/Eljefemasao/Graduation_Research/blob/development/images_for_readme/binary.png" >
</div>


<h2>Result on actual outdoor object </h2>
By applying that proposed method, youcan detect shadow region in an image.
<div>
<img alt="er" src="https://github.com/Eljefemasao/Graduation_Research/blob/development/images_for_readme/gradcam.png" >
</div>


<h2>Major Dependencies</h2>
<ul>
<li>python==3.6.3</li>
<li>Jupyter==1.0.0</li>
<li>tensorboard==1.11.0</li>
<li>tensorflow-gpu==1.11.0</li>
<li>scikit-learn==0.19.1</li>
<li>keras==2.1.3</li>

</ul>
<h2>Files/Directories</h2>
<ul>
<li>classify_seesa_keras.ipynb: main code</li>
</ul>

</body>
</html>
