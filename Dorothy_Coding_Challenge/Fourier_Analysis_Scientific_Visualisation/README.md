# Fourier Analysis: removing artifacts from scientific images

This problem consists of using Fourier analysis to remove undesired artifacts from scientific images of the Moon.

![First_View_of_Earth_from_Moon3](https://github.com/ciencialatitud0/EPIC_3/assets/30240951/9c3aa6be-de16-42ce-afb3-ef5f60377c88)

The file provided below **First_View_of_Earth_from_Moon3.jpeg** contains an image of the Moon, taken by one of the Lunar Orbiter satellites (1966 - 1967). The Lunar Orbiters (https://nssdc.gsfc.nasa.gov/planetary/lunar/lunarorb.html) were mapping the Moon by taking pictures with film cameras. The film was scanned by a machine on the satellite and sent back to Earth through radio signals. Because of the scanning method there are clear artifacts in the images. Your task is to remove them using your own Fourier-based routines.

#### Download image file:

[Dorothy_Coding_Challenge/Fourier_Analysis_Scientific_Visualisation/First_View_of_Earth_from_Moon3.jpeg](https://github.com/ciencialatitud0/EPIC_3/blob/main/Dorothy_Coding_Challenge/Fourier_Analysis_Scientific_Visualisation/First_View_of_Earth_from_Moon3.jpeg)

#### 1. Image I/O:

(a) Write a python function that reads the data from the **First_View_of_Earth_from_Moon3.jpeg** file, selects and plots one of the 3 layers of the image and returns that image layer as a python array.

(b) Briefly comment, what type of artifacts do you see in the image?


#### 2. 2D Fourier transform:

(c) Create a python function that Fourier transforms this image and returns a two-panel figure with the original image on the left and a labeled 2D plot of its Fourier image on the right.

(d) Make a slice through the middle of the Fourier image in the direction along which the artifacts are detected and plot the result. 

(e) Briefly comment, how do the image artifacts look in Fourier space?

#### 3. Masking and filtering:

(f) Create an appropriate mask for the Fourier image that matches the features associated with the image artifacts. Plot the mask.

(g) Use your mask from (f) to remove (filter out) the artifacts from the Fourier image.

(h) Inverse Fourier transform the masked Fourier image and make a two-panel figure showing the original image on the left and the new filtered image (without the artifacts) on the right.

#### 4. Artifact-free image reconstruction:

(i) Create a python function that combines all the previous steps. The function should receive an image file, apply the filter and plot the original and the filtered images. Organising this step in python classes (with functions as class methods and free parameters as class attributes is a plus).

(j) Apply the filter function from (i) to the other two channels of the image. Using the clean (filtered) output images, reconstruct the 3-layered image and make a two panel figure showing the original 3-layered image and your new artifact-free 3-layered image.

## Submission Guidelines:

- Submit the complete python code used in algorithm development and the output images in a single tar ball.
- In such tar ball, include a single Jupyter notebook for external evaluation, ensuring proper comments.
- Clearly mention any external tools or packages used. Make sure they are publicly available and free.

## Evaluation:

* Usability (20%): Your code should run smoothly, and its readability should be accessible to external evaluators.
* Interpretability (20%): Evaluation results should be quantitative and rigorous, providing a clear understanding of algorithm performance.
* Generalizability (40%): The code should work effectively on other similar, unseen images. The evaluators will test your code in a different set of images.
* Performance (20%): Evaluation of the code's speed and efficiency.
