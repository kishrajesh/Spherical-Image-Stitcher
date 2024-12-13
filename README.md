# Spherical-Image-Stitcher
Final project for our Computer Vision Class

To use, first clone the repository and import all needed libraries. Then, take images of a still scene using a tripod (preferably 24 photos at three different heights so that they cover all possible pitches (left and right).
Put the images (as jpgs) into a folder, update the variable "folder_dir" in image_stitch.ipynb with the name of the folder. Then, run the python notebook. If everything works smoothly, there should be an image called "folder_dir_resized.jpg" with the equirectangular image.

To view the image, just put it into any equirectangular image viewing software.

Some options are: https://renderstuff.com/tools/360-panorama-web-viewer/ - for viewing online on a computer or a mobile device.

Blender: Open a new project. Delete the cube in the center by right clicking and selecting "Delete", hover over the center and click Z, then click "Rendered" from the pop-up options. Then, go to the right hand panel, click on "World Properties" (should look like a red globe icon), then go to Surface->Color and click the yellow circle. Select "Environment Texture" and upload the equirectangular image. 

<img width="264" alt="image" src="https://github.com/user-attachments/assets/756aac4b-df9e-4227-9acd-4879224d769b" /> 

The scene should appear in Blender and you can move around.
