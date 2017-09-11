# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder
 
### Test Results

| epoch | batch size | keep prob | learning_rate | loss |
| ------|:----------:| -----:|------|:----------:| -----:|
|  30   |    13      |     0.5   |    1e-5       | 0.95882 |
| 100   |    13      |     0.5   |    1e-5       | 0.565314 |
| 100   |    10      |     0.5   |    1e-5       | 0.684652 |
|  20   |    10      |     0.8   |    0.001      | 0.208086 |
|  50   |    10      |     0.9   |    0.001      | 0.142004 |
| 100   |    10      |     0.9   |    0.001      | 0.0225644 |

![alt text](https://github.com/psaravind/CarND-Semantic-Segmentation/blob/master/runs/um_000015.png)
![alt text](https://github.com/psaravind/CarND-Semantic-Segmentation/blob/master/runs/umm_000035.png)
![alt text](https://github.com/psaravind/CarND-Semantic-Segmentation/blob/master/runs/uu_000071.png)

