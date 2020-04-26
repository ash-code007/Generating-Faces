# Generate-Faces
This Project is all about defining and training a DCGAN on a dataset of faces. The goal of the project is to get a generator network to generate new images of faces that look as realistic as possible!

<h2> Dataset </h2> 

<b>[CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)</b> is a large-scale face attributes dataset with more than <b>200K</b> celebrity images, each with <b>40</b> attribute annotations. The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including

1.<b>10,177</b> number of <b>identities</b>,

2.<b>202,599</b> number of </b>face images</b>, and

3.<b>5 landmark locations, 40 binary attributes</b> annotations per image.

The dataset can be employed as the training and test sets for the following computer vision tasks: face attribute recognition, face detection, landmark (or facial part) localization, and face editing & synthesis.

<h2>Results</h2>

<h2>Generator And The Discriminator Losses</h2>

The Generator and the Disciminator Networks were trained for <b>20 Epochs</b> and the Results obtained are:

![Loss](https://github.com/chaithanya21/Generate-Faces/blob/master/Results/Losses.png)

<h2> Generated Faces </h2>

![Generated Faces](https://github.com/chaithanya21/Generate-Faces/blob/master/Results/Generated%20Images.png)

<h2>Softwares and Libraries</h2>

[Python 2.7 or Higher](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Jupyter Notebook](https://jupyter.org/install)

[OpenCV](https://opencv.org/)

<h2>Project Instructions</h2>

Download the project materials from the GitHub repository by using the Download  option or Clone the github repository.After Dowloading or Cloning Navigate to the Home Folder of the Project.

```
https://github.com/chaithanya21/Generate-Faces.git
cd Generate-Faces
```
Run the following to open up the notebook server:jupyter notebook

In your browser, open face_generation.ipynb




