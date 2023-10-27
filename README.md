# Multiclass Image Classification using CNN

This project presents the code/kernel used as a final college assignment.

The aim of this project is to build a predictive model that can classify batik images based on their type using a Convolutional Neural Network (CNN) architecture.

## About Dataset:
### Batik
Batik, originating from the Javanese word meaning 'painted', uses a wax-resist dyeing process to produce colorful textiles. Developed on the island of Java, lines and patterns created in Indonesian batik are particularly symbolic, and in 2009 UNESCO named Batik in Indonesia as a Masterpiece of Intangible Heritage of Humanity.

### Content
There are 245 images (.jpg) of 5 various Indonesian Batik motifs. These motifs include:
1. Batik Ciamis
2. Batik Garutan
3. Batik Gentongan
4. Batik kawung
5. Batik Keraton

## About the project:
Several steps were taken to complete this project:
1. Explore the data by looking at the color histogram
2. Carry out the data augmentation process and change the resolution the image becomes 64 x 64
3. Separate the dataset into 80% training set, 10% validation set and 10% test set
4. Create a baseline architecture according to the AlexNet architecture image that has been included (Note: Activation function for each hidden layer uses ReLU)
5. Modifying the AlexNet architecture to get better and optimal classification results
6. Evaluate the performance of the architecture
