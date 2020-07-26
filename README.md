# Step-by-step MRI reconstruction using learned dictionaries
Material for the ISMRM 2020 educational talk

This code accompanies the educational talk given in the 2020 ISMRM Virtual Meeting:

Hands-On: Image Reconstruction
https://www.ismrm.org/20/program_files/STh08.htm

A live Q&A is planned on Thursday, 13 August 2020, 15:50 - 16:35 UTC. Change to local time-zone here:
https://www.timeanddate.com/worldclock/converter.html?iso=20200813T155000&p1=1440&p2=195&p3=240&p4=24

---
The purpose of this code is to introduce and demonstrate dictionary learning for MRI. Users will be able to replicate some of the results in the ISMRM presentation, as well as change the various parameters and see their effect.

The code uses [SigPy](https://sigpy.readthedocs.io/en/latest/) developed by by Frank Ong et al. However, not all the demo code supports running on GPU, and was not implemented with  fast, vectorized code. Therefore, there is room to greatly reduce the run-time of these algorithms.

If you are running the demo in MyBinder, the fully-sampled image dictionary learning may take upwards of 45 minutes to run. This is because the free machines are very limited. On a local four-core CPU machine, it will take about 1 minute, and the final demo will take about 10 minutes.

Jon Tamir <<jtamir@utexas.edu>>  
July 2020

## Local Install
```bash
git clone --recursive https://github.com/utcsilab/dictionary_learning_ismrm_2020
cd dictionary_learning_ismrm_2020
pip install -r requirements.txt
```
## Binder
Launch in MyBinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/utcsilab/dictionary_learning_ismrm_2020/master?filepath=Dictionary%20Learning%20Demo.ipynb)  
[Link](https://mybinder.org/v2/gh/utcsilab/dictionary_learning_ismrm_2020/master?filepath=Dictionary%20Learning%20Demo.ipynb)  
Note that the demos will run much slower in MyBinder

## Presentation slides
[Slides](presentation.pdf)

