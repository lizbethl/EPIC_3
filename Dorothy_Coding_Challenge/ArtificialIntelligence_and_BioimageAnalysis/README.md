Dorothy Coding Challenge

## Artificial Intelligence and Bioimage Analysis challenge

## Challenge Title: Zebrafish Embryo Mask Generation from Bright Field Images


## Objective
The goal of this challenge is to develop a standalone python code for creating masks of zebrafish embryos from bright field images. Participants are free to choose any image analysis algorithm, including machine learning approaches.

![Workflow](https://github.com/ciencialatitud0/EPIC_3/assets/30240951/1293f96a-973e-48f9-8442-12923e759227)

## Challenge Steps
1. Data Download
Download the image data from [Training Data](https://kondata.uni-konstanz.de/radar/de/dataset/xhEhklsaJUpbRLnY.EmbryoNet_Training-data%253A%2BWT).
Use as many images as needed for algorithm development. The images (tif, png or jpg) are located in the subfolders '../images'
2. Data Visualization
Visualize example images in a Jupyter notebook to understand dataset characteristics.
3. Algorithm Development
Develop an algorithm to generate masks. Use any algorithm, including machine learning. Provide annotated masks if using supervised learning. Manual annotations can be done using any free software such as [LabelMe](http://github.com/wkentaro/labelme).
Clearly document the algorithm steps in the code.
4. Evaluation
Evaluate the algorithm on images from [Evaluation Data](https://kondata.uni-konstanz.de/radar/de/dataset/gckMwoUnrbKCTVDV.TwinNetworkDataZebrafish_Temperature).
Include comprehensive metrics in the evaluation, such as accuracy, precision, recall, etc. Feel free to include as many metrics as you consider necesary.
Provide a Jupyter notebook showcasing the entire process, including raw image loading, masking, and result analysis. Comment on each step.

## Submission Guidelines
Submit the complete code used in algorithm development.
Include a Jupyter notebook for external evaluation, ensuring proper comments.
Clearly mention any external tools or packages used. Make sure they are publicly available and free.

## Evaluation
Usability (20%): Your code should run smoothly, and its readability should be accessible to external evaluators.
Interpretability (20%): Evaluation results should be quantitative and rigorous, providing a clear understanding of algorithm performance.
Generalizability (40%): The code should work effectively on other similar, unseen images. The evaluators will test your code in a different set of images.
Performance (20%): Evaluation of the code's speed and efficiency.

## Note
This challenge provides an opportunity to showcase your skills in bioimage analysis, artificial intelligence, and algorithm development. Thorough documentation and detailed analysis of results are encouraged. Good luck!