- This folder contains source code of three different models in notebook format (.ipynb)
	- The three models are: 
	- 1) ResNet 50
	- 2) ResNet 50 - VGGFace - ResNet50 + improved concatenate operations
	- 3) ResNet50 + improved concatenate operations + multiple dense layers

- "requirement.txt" - contains all the dependencies when the source code was run in a local python 3.6 environment

- If running the code in collab, you may get "AttributeError: 'str' object has no attribute 'decode'" while training
	- Please update saving.py file by removing ".decode('utf8')"
	- Restart runtime after updating the code