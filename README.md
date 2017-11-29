# GNN-for-OOKB  
  
#How to use  
download or clone this repository.  
unzip each dataset in dataset dir   
python main.py  

#Requirements
chainer  
cuda or numpy  
more_itertools  

#How to improve
add your models in models dir.
register your models in models/manager.py     
use option -nn to use your models, e.g., "python -nn X" runs the model X  

#How to undarstand results  
run draw-score-history/draw.py with your threshold  
this script show learning history of positive and negative triplets's scores  
(checking examples is easiest way to understand this)  
  
#How to cite this work  
officia paper: https://www.ijcai.org/proceedings/2017/0250.pdf  
official bibtex : https://www.ijcai.org/proceedings/2017/bibtex/250  
