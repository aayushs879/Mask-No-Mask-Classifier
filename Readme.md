# Mask No Mask Classification

## Dataset Description
The dataset used consisted of roughly 6000 masked images of faces and 9000 images cropped to the faces.

## Approach
In this approach resnet18 pretrained on Imagenet Data has been fine tuned for the task. The validation accuracy obtained is 99%. However that number doesn't do justice to the model. The model's weak area has also been shown in the inference notebook which comes out to be the faces with beard or pimples. 


<br>
<hr>
<br>

## Note
For Inference we first detect the face from the image using Retinaface detector and then pass the image to model.
