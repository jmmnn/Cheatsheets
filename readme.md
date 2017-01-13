#Some handy commands

#installing Miniconda

wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -O miniconda.sh 
bash miniconda.sh -p miniconda

##Creating a new conda environment
conda create --name cybersecu pandas numpy

##Activating it
source activate cybersecu

##Git cloning from a branch:
git clone https://github.com/ICT4SD/CyberSecurity_Strategies.git -b Fordham_DesignLab

