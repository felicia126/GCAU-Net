# GCHA-Net

This code is for the paper title 'GCHA-Net: Global context and hybrid attention network for automatic liver segmentation' 


# dataset 
LiTS2017：https://competitions.codalab.org/competitions/17094#participate

3D-IRCADb 01：https://www.ircad.fr/research/3d-ircadb-01/



# How to use this code

1. Download nnUNet framework from the website:https://github.com/MIC-DKFZ/nnUNet, and use the following commands:

git clone https://github.com/MIC-DKFZ/nnUNet.git (note: nnUNetv1 version)
cd nnUNet
pip install -e .

2. The above files including GCHA_Net.py is put into the fold: nnunetv2\training\nnUNetTrainer\variants\network_architecture.

3. put the file named as 'run_training.py' into the folder 'nnunet\run'

4. run the command 'python run_training.py'.

If you encounter any problems, please do not hesitate to contact us.


# GCAU-Net, please cite this paper

H. Liu, Y. Fu, S. Zhang, J. Liu, Y. Wang, G. Wang, J. Fang,GCHA-Net: Global context and hybrid attention network for automatic liver segmentation,Computers in Biology and Medicine, 152:(106352), 2023. https://doi.org/10.1016/j.compbiomed.2022.106352.

