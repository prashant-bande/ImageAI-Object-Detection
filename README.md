1. Create an Anaconda environment with python version 3.6.

conda create -n retinanet python=3.6 anaconda

2. Activate the environment and install the necessary packages.

source activate retinanet
conda install tensorflow numpy scipy opencv pillow matplotlib h5py keras

3. Then install the ImageAI library.

pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.1/imageai-2.0.1-py3-none-any.whl

4. Now download the pretrained model required to generate predictions. This model is based on RetinaNet (a subject of a future article). 

	Click on the below link to download – RetinaNet Pretrained model 
	
	https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5
	
5. Copy the downloaded file to your current working folder

6. Open jupyter notebook and execute the codes: