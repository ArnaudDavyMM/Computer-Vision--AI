Overview :

Traumatic injury is the most common cause of death in the first four decades of life and a major public health problem around the world. There are estimated to be more than 5 million annual deaths worldwide from traumatic injury. Prompt and accurate diagnosis of traumatic injuries is crucial for initiating appropriate and timely interventions, which can significantly improve patient outcomes and survival rates. Computed tomography (CT) has become an indispensable tool in evaluating patients with suspected abdominal injuries due to its ability to provide detailed cross-sectional images of the abdomen.

Abdominal trauma is among the most common types of traumatic injury, with the most frequent cause being motor vehicle accidents. Abdominal trauma may result in damage and internal bleeding of the internal organs, including the liver, spleen, kidneys, and bowel. Detection and classification of injuries are essential to effective treatment and favorable outcomes. A large proportion of patients with abdominal trauma require urgent surgery. Abdominal trauma often cannot be diagnosed clinically by physical exam, patient symptoms, or laboratory tests.

Prompt diagnosis of abdominal trauma using medical imaging is thus critical to patient care. AI tools that assist and expedite the diagnosis of abdominal trauma have the potential to substantially improve patient care and health outcomes in the emergency setting.

Why this project?

Well, Biomedical imaging or Computed Tomography scans (CT Images) analysis is relevant and presents many specific challenges I was not aware of to work with. Below are the main challenges I faced:
1. Specific medical image format: Biomedical imaging uses DICOM and NIFTI formats. The main difference between these two formats is that the DICOM format has multiple 2D image slices which together form a 3D image, whereas the NIfTI format has only one file that contains the 3D image.
2. Data annotation: Medical image data often requires expert annotation, which can be time-consuming and expensive. Additionally, there can be variations in annotation quality and consistency, which can affect the performance of the segmentation model.
3. Data Ambiguity and Complexity: Medical images can be complex and heterogeneous, with variations in image quality, resolution, and modality (Image variability). This can make it difficult to develop accurate, robust DL models and techniques such as segmentation models to just name that.
4. Model interpretability: Medical image segmentation models can be difficult to interpret, making it challenging to understand how the model is making its predictions.
5. Training instability: Deep learning models can be sensitive to the choice of hyperparameters and the quality of the training data, which can lead to training instability and poor performance.
6. Computational complexity: Large datasets and high-dimensional images require substantial computational resources and time.
7. Data access: Medical image data is often subject to strict privacy regulations, which can make it difficult to access and use for research purposes.

To overcome these challenges, it is important to carefully use appropriate preprocessing techniques, and carefully annotate the data, design and evaluate the segmentation model. Additionally, it was necessary to use specialized tools and frameworks, such as DLTK, to enable image preprocessing, data visualization, and deep learning on biomedical images and improve the performance of the model.
