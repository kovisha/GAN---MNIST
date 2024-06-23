# GAN - MNIST Handwritten Dataset

Steps

1. Design and Train a GAN on MNIST dataset so that Generator G can create random fake digit images.

2. Save G.pkl and D.pkl

3. Use the Generator G to create a dataset of 100 fake digits images (S1)

4. Save the latent samples and fake images to a Folder "Fake_Digits"

5. Train a CNN Classifier to classify the images

*   Take 100 random samples from real dataset (S0)
*   Save the classifier trained as C.pkl
*   Obtain Classification error for S0 and S1.
*   While using S1 - (Use torchvision.Datasets.ImageFolder)

6. Architecture required if we need to generate specific images is illustrated
