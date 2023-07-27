# Face-Mask-Image-Classification

Background: Given the current crisis the world is facing, facemask and social distancing has become part of the norm in most places. However, many people are still not obeying the guidelines presented by the government and this has caused the spread of the virus to increase at a near uncontrollable rate. Therefore, there is a need to create a detection system that could be implemented to a simple device like a smart mirror placed strategically at the entrance of popular venues. This could help remind the people or deter people from forgetting or ignoring the current health safety regulations and guidelines.

Data: This dataset consist of more than 800 images classified into 2 classes: with mask, and without mask. The photos are scraped from Unsplash by author engin akyurt. For our purposes, the dataset has been manually split into test and train folders each consisting of 2 classes mentioned above. https://unsplash.com/photos/AS-ksEGPa2c

Approach: For the first part, I will take a sample of the image and create a function for outlying a box around faces it detects. Then will create a social distancing rule by using the euclidean method. Since am still new to computer vision, will build and train models on various machine learning algorithms before choosing one that I think suits best for the dataset and future inputs.

Deliverables: - plan to have a working base model that could be easily implemented into the smart mirror in my house. I will fine tune and improve the model as I learn more about ML.
