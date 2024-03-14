Converting Real Photographs to Chinese Landscape Painting Style with CycleGAN and DCGAN 

Code reference
Referred to other authors' base code frameworks as a starting point, and modified and optimized them accordingly to the specific needs and goals of my project.


CycleGAN
Existing code frameworks were referenced and based on which necessary modifications and adjustments were made to suit specific research needs and objectives.

reference source:  Monet-CycleGAN/cyclegan.ipynb at master · NitishaS-812k/Monet-CycleGAN (github.com) 


DCGAN
Existing code frameworks were referenced and based on which necessary modifications and adjustments were made to suit specific research needs and objectives.

reference source: Monet-paintings-DCGAN-Deeplearning/monet-painting-gan-4.ipynb at main · shriyutha/Monet-paintings-DCGAN-Deeplearning (github.com)


LLM disclaimer
1.	When some of the code was running incorrectly, I tried to get help from ChatGPT.
2.	I used ChatGPT to help me understand some complex code.
3.	I asked ChatGPT to give me some advice on the use of specific vocabulary.


Dataset
chinese landscape painting
A folder containing thousands of Chinese paintings

Photo
A folder containing thousands of photos of real landscapes.

CycleGAN.ipynb
A network containing two generators and two discriminators enables it to learn to convert bidirectional between landscape photos and landscape paintings.


DCGAN.ipynb
A four-layer convolutional neural network with LeakyReLU activation function as a discriminator, and an inverse convolutional layer using ReLU activation and batch normalization as a generator.


Generate image

CycleGAN model
    


        
 
