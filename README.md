# automotive_dl
Code for the seminar Applied Deep Learning in the Automotive Industry and Industry 4.0

# Environment
Using Anaconda create a new environment and install the following packages:

`conda install -c conda-forge opencv`

`conda install pytorch torchvision -c pytorch`

`conda install matplotlib`

`conda install pandas`

`pip install torchsummary` 

# Berkeley Dataset
The Berkeley dataset must be downloaded and placed into the following subfolders:

**Segmentation** should be placed in `data/bdd100k/seg`

The Dataloaders will look for the files in the following locations:

**Training**: `data/bdd100k/seg/images/train` and `data/bdd100k/seg/labels/train`

**Validation**: `data/bdd100k/seg/images/val` and `data/bdd100k/seg/labels/val`

**Test**: `data/bdd100k/seg/images/test` and `data/bdd100k/seg/labels/test`

# Initial Setup
After downloading the dataset you must create the file lists by running the `gen_lists.ipynb` notebook. This will create a new folder `data/bdd100k/lists` containing lists of image names for the training, validation and test sets.

Also create a folder `model` to allow saving and loading of the network weights.
