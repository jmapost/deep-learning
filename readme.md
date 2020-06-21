# My practice repo for deep-learning.  

Created: May 22, 2020  
Author: Jennifer E. Yoon

## My exercises for Chollet, Deep Learning with Python book  

  * Appendix: setup, tensorflow, keras, GPU on AWS EC2. * Started watching class 5 sequence models.  
    AWS EC2 GPU large instance still too expensive, 70 cents/hour. Use Google CoLAB free GPU instances instead. 
  
  * Chp 9: Conclusions 
    Key Concepts Review, how to keep-up with new developments, future of deep learning, limitations of deep learning
  
  * Chp 4.5: Universal Workflow of Deep Learning  
  
  * Chp 5: Convolutional Networks -- has vision recognition examples.  
  
---     

## Coursera.org Deep Learning.AI Specialization - moved here  
  * June 8, 2020 start transfer of files from "learn-mldl" repo to "deep-learning" repo - Done.  

#### DLAI Class 3 - Structuring ML Projects  
  * June 9, 2020 - began rewatching videos, at 9/22 on Youtube playlist.  
  
#### DLAI class 4 CNN 
  * As of June 1, 2020 Monday, current notebook versions have been copied here.    
  * Week 1 quiz #9 question on answers.  
  * Sub tensorflow intro notebook with version tf 2.2.  Class uses tf 1.2.  
  * Next, finish week 3 and 4 notebooks. Style Transfer, Face Recognition.  
  
#### DLAI class 5: Sequence Models 
  * May 23, 2020 -- started watching videos.  

---  

## Setup and Environment notes  

  * June 20, 2020 -- Use **conda env dlpy** on Ubuntu-side to run python.  
      - Even though repo is stored on C drive (for Google Drive backup), can run from Ubuntu terminal using conda3 Ubuntu version. 
  * June 20, 2020 -- merged with Ubuntu repo version.  Ubuntu side repo deleted. 
  * June 17, 2020 1:00 AM - moved local repo to C drive, Google Drive backup does not work well with Ubuntu "network" drive, can only backup as Photos, forces other file folders to backup as Photos.  
  * deep-learning repo - recloned and tested on C:\python\repos\deep-learning\  

.bashrc alias: "adlpy" changes active conda env to "dlpy" and changes working directory to "/work/deep-learning".  Python v 3.8, tensorflow v 2, keras, tensorflow-datasets.  Coursera uses hdf5 data library - already installed.  Doctest and Pandocs already installed - use for my testing.  Later install unittest.  

Conda3 "base" env uses Python v 3.7. Has deep learning packages for Coursera DLAI class and Stanford CS231n class.  

### Use conda env "dlpy" on Ubuntu, CPU x86 laptop:  

  * From Ubuntu terminal, type "code" to start VS-Code-Ubuntu version.    
  * From VS-Code, Select Python Interpreter, "~/home/conda3/envs/dlpy/bin/...  
  * Open deep-learning file from C drive:  File - Open - (show local files button)  
  * Select python code lines, then: Run selection in Python Terminal (Shift+Alt+Enter)  
      - will activate **dlpy env** on Ubuntu and run selected code lines.  
  * From there on, all python modules imported will be "dlpy" Ubuntu versions.  
  
Ubuntu-side "dlpy" env has python v 3.8, tensorflow v 2.2 installed using pip.    




