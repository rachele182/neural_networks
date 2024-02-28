### <font color="green"> <span style="font-size:larger;"> Contents of Four_Classes_Classification: </font> </span>

Here afther a brief description of the contents of the folder.   
For each design and training an analyis of the results in terms of Confusion Matrices and Roc Curves is reported.

- **task_4classes_1.ipynb**:
    - it contains the code to design a **from-scratch CNN** used to classify between benign mass, malign mass, benign calcification and malign calcification patches in a set of mammography images. 
- **task_4classes_2.ipynb**:
    - it contains the code to design a **pre-trained CNN** benign mass, malign mass, benign calcification and malign calcification patches exploiting the data augmentation technique to try to improve performance.
 - **task_4classes_3.ipynb**:
    - it contains the code to design a **an Ensemble CNN** used for the same classification as an average weighted media of three CNNs trained on different dataset:
     1. from scratch CNN from *task_4classes_1*;
     2. pre-trained *VGG16*;
     3. *InceptrionV3*

All the files are written in python language as part of Jupiter Collab notebook (please remember that the code is copyrighted by Universita´di Pisa).   
In each cell you can visualize the obtained result. Please seutp workspace and collab notebook to run locally the codes. 
