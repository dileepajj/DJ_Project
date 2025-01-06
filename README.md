# DJ_Project

Name: Dileepa Joseph Jayamanne <br>
Student ID: 22031359 <br>

Project Title: Classification of age group, gender and race from facial images using deep convolutional neural networks with transfer learning 

Best VGG Models:
1) Best Multi-Task Learning (MTL) based code with ImageNet weights <br>
Folder 2: MTL_based_VGGmodel_ImageNetweights_with_fully_trainable_layers.ipynb (6th file)

2) Best Multi-Task Learning (MTL) based code with VGGFace weights: <br>
Folder 3: MTL_based_VGGmodel_ImageNetweights_with_fully_trainable_layers.ipynb (6th file)

3) Alternative comparable partially trainable models with gender embedding (GE) and gating mechanism (GM) or attendtion mechanism (AM) <br>
3.1) with ImageNet weights: <br>
     Folder 2: GE+GM--> MTL_based_VGGmodel_ImageNetweights_v4.ipynb (4th file)<br>
     Folder 2: GE+AM--> MTL_based_VGGmodel_ImageNetweights_v5.ipynb (5th file)<br>
3.2) with VGGFace weights: <br>
     Folder 3: GE+GM--> MTL_based_VGGmodel_VGGFaceweights_v4.ipynb (4th file)<br>
     Folder 3: GE+AM--> MTL_based_VGGmodel_VGGFaceweights_v5.ipynb (5th file)<br>

4) Best CNN model that doesn't use transfer learning <br>
   Folder 4:  (file 4) <br>

5) Best STL-VGG models:<br>
   <li> Folder 5: Age group classification: (file 1)</li>
    <li> Folder 5: Gender classification: (file 2)</li>
     <li> Folder 5: Race classification:  (file 3)</li>
     
 6) Best MTL-VGG19 model
    Folder 6: fullytrainable.. (file 2)

 7) Best MTL-ResNet50 model
    Folder 7: fullytrainable.. (file 2)

8) Best MTL-DenseNet121 model
   Folder 8: fullytrainable.. (file 2)




Project aim: To classify age, gender, and race from facial images using deep convolutional neural networks with transfer learning.
Plan:
<li> Compare several deep architectures for all classifications. </li>
<li> Investigate whether subsetting facial images based on gender and race enhances the accuracy of the age group classification.</li>


Dataset: UTKFace dataset (University of Tennessee, Knoxville Face dataset)
https://susanqq.github.io/UTKFace/
