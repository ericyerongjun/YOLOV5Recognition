# YOLOV5Recognition
Something you need to do:
1. Capture some images for different classes (more than 70 images from training will be more precise, otherwise the model will be unable to recognize the images you tested)
2. Annotate the images taken using makesense.ai (An url)
3. Train the model's weights using google colab with the ipynb offered here

Training:
In cust_data.yaml
Class 0: The first label (Example: In makesense:Stop Then here is stop)
Class 1: The second label

Makesensi.ai
Actions -> Export Annotations -> A zip package containing files in YOLO format -> Export -> Save the zipped file in the desktop

Create a folder called train_data with a folder called photos, a folder of text and a file cust_data.yaml

Unzip the zipped file and copy and paste the text in the folder to the text folder

Zip the folder train_data and copy the zipped file into the content of colab

Choose the runtime T4GPU

Run the colab

You can try to increase the epochs to get a more precise model

Drag some sample images to the check folder in colab (not folder or zip file, but a bunch of images)


