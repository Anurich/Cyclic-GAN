<h2>Paper.</h2>
https://arxiv.org/pdf/1703.10593.pdf

<h2> Cycle-Consistent Adversarial Network.  </h2>
Image-to-image translation is a class of vision and graphics problems where the goal is to learn the mapping between an input image and an output image using a training set of aligned image pairs. However, for many tasks, paired training data will not be available. <b> Cycle-Consistent  Adversarial Network </b> is an approach for learning to translate an image from a source domain X to a target domain Y in the absence of paired examples.

<h2>Project Overview.</h2>
In this work, I wrote the program to do image to image translation in the absence of training data. The code written in this directory is based on paper of <b> Cycle-Consistent Adverserial Networ </b>. I used two network one is Generative network and another is Discriminator network, The task for generative network is to generate the fake images where as discriminative network is used to dscriminate between original and fake images.

<h2> Installation. </h2>
<ul>
  <li>
    python == 3.6.6
  </li>
  <li> 
    tensorflow==2.4.0
  </li>
</ul>

<h2> Loss.</h2>
Loss used are three.
<ul><li>
    Discriptive Loss.
  </li>
  <li>
    Generative Loss.
  </li>
  <li>
    Cyclic Loss.
  </li>
</ul>

<h2> Important Note.</h2>
<ul>
  <li>The model is not trained fully, its only trained for 20 epoch.</li>
  <li>Model is trained on CPU.</li>
  <li> In order to train on GPU, one need to enable the GPU support.</li>
</ul>
<h2> Contribute. </h2>
I would really appreciate any suggestion, or any complain about the code. As well feel free to contribute to the project. 
