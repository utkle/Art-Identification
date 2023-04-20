Project Overview

This machine learning project aims to identify the painter of a painting from an image using deep learning techniques. The purpose of this project is to provide a tool that can help with the authentication and verification of artwork, and to prevent the spread of forgeries and imitations in the art market.

The Metropolitan Museum of Art can use this model to determine the authenticity of paintings attributed to five artists: Van Gogh, Durer, Picasso, Titian, and Rembrandt. By analyzing the unique style and characteristics of each artist's work, the model can compare a new painting to known works by the same artist and provide an expert opinion on its authenticity.

The project involves several key phases, including data preprocessing, model training, and evaluation using metrics such as accuracy.

Data

The dataset used for this machine learning project is the "Best Artworks of All Time" dataset obtained from Kaggle, which contains over 8,400 paintings by 50 influential artists. The data was scraped from artchallenge.ru in February 2019. The model is trained to identify paintings by five of these artists, namely Van Gogh, Durer, Picasso, Titian, and Rembrandt.

Project Steps

The project involved several key phases. Firstly, an exploratory data analysis was conducted to understand the distribution of the data. The image data was then preprocessed using data augmentation techniques, such as resizing the images, converting them to RGB, and normalizing pixel values.

Next, baseline convolutional neural network models were created, followed by more advanced models using transfer learning techniques such as pre-trained models like VGG16 and VGG19. The models were evaluated on a hold-out test set, and the best-performing model was identified based on accuracy. The evaluation metric for this project is accuracy.

Results

The initial accuracy of the baseline models was 0.66, and the best results were achieved using the VGG19 model with a transfer learning approach, achieving an accuracy of 0.81.

Summary

In summary, this machine learning project utilizes deep learning techniques to identify the painter of a painting from an image. By training the model on a dataset of paintings by five prominent artists, the Metropolitan Museum of Art can use the model to verify the authenticity of paintings attributed to Van Gogh, Durer, Picasso, Titian, and Rembrandt.

This project can be used to prevent the spread of forgeries and imitations in the art market, which helps to ensure its integrity. The dataset used for training the model is the "Best Artworks of All Time" dataset obtained from Kaggle, which contains over 8,400 paintings by 50 influential artists.

The project involves several key phases, including exploratory data analysis, data preprocessing, model training, and evaluation. The best-performing model was identified based on accuracy, achieving an accuracy of 0.81 using transfer learning with the VGG19 model. Overall, this project has significant implications for the art market, and it provides a useful tool for museums, collectors, and dealers in verifying the authenticity of paintings.
