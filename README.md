# ImageSegmentation
Image Segmentation with different maxflow / mincut algorithms: Karger, Boykov-Kolmogorov, Pymaxflow and Push Relabel.

The main components of the project are the following: 

- IMAGES is folder with a selection of images, downloaded form internet
- IMAGE SEGEMENTATION contains the core of the code, including: 
  - GUI: processes the image and enables to integrate the scribbles
  - IMAGE: PREPROCESSING calcultates the weights of the graph created from the image and the scribbles
  - GRAPHCUT: contains the different maxflow mincut algorithms, implemented from scratch; as well as the Superpixel file that transforms an image before being processed by the Karger algorihtm
- main.py (and test.py): file that needs to be run, bring all elements together

