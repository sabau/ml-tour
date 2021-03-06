# Machine learning Talk 2018-04-10

We will discover some of the main features and implement them on a Jupyter notebook.
this repo will contain both the slides and the original file as long as some checkpoints to fast-forward some part of the presentation and skip the trainig of our neural networks.

## Supervised

This is the most generic and introductory task, we will use the same example that will be refined on the ConvNet, and see how they will differ.

## Unsupervised

A classical unsupervised task is the categorization or encoding/decoding. The latter is far more discussed at this moment, but almost never used in practice, so we will focus on a more classical categorization problem
We will see kNN and naive Bayes and when to use one or the other.

## Convolutional NN

In this section we will discover why conv nets surpasses classical method for data where correlations between dimensions does matter.
The example will focus on images and in particular on how close pixels influences one another, where on classical NN the concept of neighbour is not exploited.## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```
git clone https://github.com/sabau/ml-tour.git
cd ml-tour
```

5. (Optional) __If you plan to install TensorFlow with GPU support on your local machine__, follow [the guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system.  If you are using an EC2 GPU instance, you can skip this step.

6. (Optional) **If you are running the project on your local machine (and not using AWS)**, create (and activate) a new environment.

	- __Linux__ (to install with __GPU support__, change `requirements/dog-linux.yml` to `requirements/dog-linux-gpu.yml`):
	```
	conda env create -f requirements/tb-linux.yml
	conda install -c anaconda pandas
	source activate ml-intro 
	```
	- __Mac__ (to install with __GPU support__, change `requirements/dog-mac.yml` to `requirements/dog-mac-gpu.yml`):
	```
	conda env create -f requirements/dog-mac.yml
	conda install -c anaconda pandas
	source activate dog-project
	```
	- __Windows__ (to install with __GPU support__, change `requirements/dog-windows.yml` to `requirements/dog-windows-gpu.yml`):
	```
	conda env create -f requirements/tb-win.yml
	activate ml-intro
	```

9. Switch [Keras backend](https://keras.io/backend/) to TensorFlow.
	- __Linux__ or __Mac__:
		```
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
		```
	- __Windows__:
		```
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
		```

10. (Optional) **If you are running the project on your local machine (and not using AWS)**, create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `dog-project` environment.
```
python -m ipykernel install --user --name dog-project --display-name "dog-project"
```

11. Open the notebook.
```
jupyter notebook 
```

12. (Optional) **If you are running the project on your local machine (and not using AWS)**, before running code, change the kernel to match the ml-intro environment by using the drop-down menu (**Kernel > Change kernel > ml-intro**). Then, follow the instructions in the notebook.
