# DJ_Project

Name: Dileepa Joseph Jayamanne <br>
Student ID: 22031359 <br>

Project Title: Classification of age group, gender and race from facial images using deep convolutional neural networks with transfer learning 

<ul>
     <li>This work investigates the performance of single-task learning (STL) and multi-task learning 
(MTL) approaches for classifying age group, gender, and race from facial images in the 
UTKFace dataset.</li>
<li>STL-based VGG models were initially employed for individual classifications, 
achieving test accuracies of 92.2% for age group, 98.1% for gender, and 94.3% for race. </li>
<li>MTL models were subsequently introduced to perform all three tasks simultaneously, leveraging 
standard deep learning architectures like VGG16, VGG19, ResNet50, and DenseNet121, with 
transfer learning and fully connected layers appended to a shared convolutional base. </li>
<li>Additionally, a fully trainable MTL model without transfer learning was developed for 
benchmarking. </li>

<li>Results highlight that MTL models with VGG16 convolutional base tend to outperform STL
based models in both accuracy and F1-scores, for age group, gender and race classifications 
of UTKFace data. </li> <li>The best MTL model, utilizing a VGG16 base with ImageNet weights, 
achieved test accuracies of 92.5%, 98.2%, and 95% for age group, gender, and race, 
respectively. Using VGGFace weights yielded comparable classification performance with 
91.8% for age group, 97.9% for gender and 95.6% for race.</li><li>Partially frozen MTL-VGG models, 
incorporating gender embeddings with gating or attention mechanisms, demonstrated 
competitive performance with significantly reduced parameter counts.</li> <li>Overall, the MTL 
approach not only improves performance but also reduces the computational overhead 
associated with training separate models for individual tasks, establishing its efficacy for multi
faceted classification tasks.  </li></ul>


## Organisation of code files in GitHub
<b>Best VGG Models:</b>
1) Best Multi-Task Learning (MTL) based code with ImageNet weights <br>
Folder 2: MTL_based_VGGmodel_ImageNetweights_with_fully_trainable_layers.ipynb (file 6)

2) Best Multi-Task Learning (MTL) based code with VGGFace weights: <br>
Folder 3: MTL_based_VGGmodel_ImageNetweights_with_fully_trainable_layers.ipynb (file 6)

3) Alternative comparable partially trainable models with gender embedding (GE) and gating mechanism (GM) or attendtion mechanism (AM) <br>
3.1) with ImageNet weights: <br>
     Folder 2: GE+GM--> MTL_based_VGGmodel_ImageNetweights_v4.ipynb (file 4)<br>
     Folder 2: GE+AM--> MTL_based_VGGmodel_ImageNetweights_v5.ipynb (file 5)<br>
3.2) with VGGFace weights: <br>
     Folder 3: GE+GM--> MTL_based_VGGmodel_VGGFaceweights_v4.ipynb (file 4)<br>
     Folder 3: GE+AM--> MTL_based_VGGmodel_VGGFaceweights_v5.ipynb (file 5)<br>
     
<b>-------------- Other Models ---------------------</b> <br><br>
4) Best CNN model that doesn't use transfer learning <br>
   Folder 4: MTL_based_CNNmodels_noTransferLearning_v1.ipynb (file 1)<br>

5) Best STL-VGG models:<br>
   Folder 5: Gender classification: 1_STL_VGGmodel_imagenet_weights_for_gender_classification.ipynb (file 1)<br>
   Folder 5: Age group classification: 2_STL_VGGmodel_imagenet_weights_for_age_group_classification.ipynb (file 2)<br>
   Folder 5: Race classification: 3_STL_VGGmodel_imagenet_weights_for_race_classification.ipynb (file 3)<br>
     
6) Best MTL-VGG19 model<br>
    Folder 6: fully trainable: MTL_based_VGG19model_ImageNetweights_with_fully_trainable_layers.ipynb (file 2) <br>

7) Best MTL-ResNet50 model <br>
    Folder 7: fully trainable: MTL_based_ResNetmodel_ImageNetweights_with_fully_trainable_layers.ipynb (file 2) <br>

8) Best MTL-DenseNet121 model <br>
   Folder 8: fully trainable: MTL_based_DenseNet121_model_ImageNetweights_with_fully_trainable_layers.ipynb (file 2) <br>


## Google Colab Links
Since UTKFace data exceeds the size the GitHub can host, it is stored in Google drive. <br> 
<br>
GE: Gender Embedding, GM: Gating Mechanism, AM: Attention Mechanism <br>
1) MTL-VGG16 based models with ImageNet weights
   <br> i)  Best Model: <br> https://drive.google.com/file/d/10Kan0Ip1Nip8ltLkCFuwevvrxMpsrFlZ/view?usp=drive_link
   <br> ii) Comparable model with GE + GM : <br> https://drive.google.com/file/d/1k56SYaE2zaqamPaZyinv3FklwQg98clu/view?usp=sharing
   <br> iii) Comparable model with GE + AM: <br> https://drive.google.com/file/d/1yECWUw_jgcrrkNrQ5h1qDgFBjBAht00f/view?usp=sharing

2) MTL-VGG16 models with VGGFace weights <br>
   i)  Best Model: https://drive.google.com/file/d/1qkO2akyCRlBNm6FTq2PKr8lDQkLit8Hj/view?usp=sharing
   <br> ii) Comparable model with GE + GM : <br> https://drive.google.com/file/d/1JhLbxEvNIYmr3DD9YD3NMpNb868dvQlp/view?usp=sharing
   <br> iii) Comparable model with GE + AM: <br> https://drive.google.com/file/d/1xx4W1Yj8ezneAot4Gog6lvboNynYceic/view?usp=sharing
   <br>
3) Custom CNN model: <br>
   This file includes the following models: <br>
    i) Best CNN model<br>
    ii) CNNbase + GE <br>
    iii) CNNbase + GE + GM <br>
    iv) CNNbase + GE + AM <br>
    Link: https://drive.google.com/file/d/15TsPFrAgBQuJqWrm54Sc5kX-EfuVrdKP/view?usp=sharing
    <br>
4) Single-Task Learning VGG based best models:
   <br>i) Gender Classification: <br> https://drive.google.com/file/d/174LA49-VeGeJ4jZWptPRTZgMQ8bvniY4/view?usp=sharing
   <br>ii) Age Group Classification: <br> https://drive.google.com/file/d/1irPhSomguSpy-88n8JbXDO0rCuALk7zs/view?usp=sharing
   <br>iii) Race Classification: <br> https://drive.google.com/file/d/1qD8zoZ9oDxCD9aeB1pO3z1ohpXF1hP8D/view?usp=sharing
   <br>
5) Best VGG19 model: <br>
   https://drive.google.com/file/d/1D6bsKKmgV588f7AJ0lCPvPW6mZE6H_wa/view?usp=sharing
   <br>
6) Best ResNet50 model <br>
   https://drive.google.com/file/d/1_wHjyNI7LJzNzXglMHkqAJwgqWl-hIbR/view?usp=sharing
   <br>
7) Best DenseNet121 model<br>
   https://drive.google.com/file/d/1qjtk9cKhRa6rO9KVJ-oYLsJGpBKcriGJ/view?usp=sharing
   <br>
8) Hyperparameter Tuining (Folder 1 file links):<br>
   8.1) 1_initial_hyperparameter_tuning_FC1nodes_VGGmodel:  
   https://drive.google.com/file/d/1gwPMVIdN7yxVLpNIzOZwz2HSSuVAtswb/view?usp=sharing
   <br> 8.2) 2_hp_tuning_learning_rates_and_bsizes_STL_VGGmodel_for_gender_classification
   <br> https://drive.google.com/file/d/16S_nN2yqWCmTBDnvAl9q2cvAPmcdm_kR/view?usp=sharing
   <br> 8.3) 3_hp_tuning_learning_rates_and_bsizes_MTL_VGGmodel_for_all_classifications_v1
   <br> https://drive.google.com/file/d/1V4pZ-BpIg8erbQO4OnXErN2JEOEiox5H/view?usp=sharing
   <br> 8.4) 3.1_hp_tuning_learning_rates_and_bsizes_MTL_VGGmodel_for_all_classifications_v2
   <br> https://drive.google.com/file/d/1eB-M4FyC4Mi7pw0ooh7Y0rmOHtllKawv/view?usp=sharing
   <br> 8.5) 4_hp_tuning_learning_rates_and_bsizes_MTL_ResNet_model_for_all_classifications_v1
   <br> https://drive.google.com/file/d/1N2wf1ca6b7x5TdE0Ht1cAKcO50kEwYRQ/view?usp=sharing
   <br> 8.6) 5_hp_tuning_learning_rates_and_bsizes_MTL_ResNetmodel_for_all_classifications_v2
   <br> https://drive.google.com/file/d/1U2RPUqv15BDF4rs8MKE-aq-UL0bIN9vi/view?usp=sharing
   <br>



   
   
   


Dataset: UTKFace dataset (University of Tennessee, Knoxville Face dataset)
https://susanqq.github.io/UTKFace/
