# DIFFSINGER

## DIFFSINGER 학습환경 구성

### GCP를 활용한 VM

git clone https://github.com/MoonInTheRiver/DiffSinger.git

source activate "ENV_NAME"

**install requirements.**

pip install -U pip

pip install Cython numpy==1.19.1

conda install pytorch==1.9.0 torchvision==0.10.0 torchaudio==0.9.0 cpuonly -c pytorch

pip install -r requirements.txt

https://github.com/MoonInTheRiver/DiffSinger/blob/master/docs/README-SVS-opencpop-cascade.md
