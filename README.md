# GTAVCNNProject
## Goal: Use deep learning related algorithms to autonomously drive a car in GTA V environment in real time 

## Questions:
* whether should we solve it using end-to-end driving or other techniques?
* where are the resources for sending command to GTA V using deep learning in Windows?
* how to collect datasets in GTA V?

## Reconsider the autonomous driving simulators:

### Simulator's pros and cons:

#### 1. GTA V
  ##### pros: <br />
    * has near-real environment with red lights, stop signs, pedestrians and so on
    * may be build in OpenAI's universe environment in future
  ##### cons: <br />
    * not an open source environments. Therefore we may have to concern about the license issue 
    * by now, no information can be got about the real positions of other vehicles and pedestrians in the game 
    * have to be run in windows environment
    * I doubt one GPU can run both GTA V and deep learning (ConvNet) in real time (maybe even 10 FPS). In other words, high hardware requirements
#### 2. TORCS
  ##### pros: <br />
    * can get real time data of other car's real locations
    * have existing source codes for self driving in TORCS
    * low hardware requirements 
  ##### cons: <br />
    * no pedestrians, lights and stops signs available

### Online resources: <br />
#### 1. Deep drive(include source code) <br />
  * link: http://deepdriving.cs.princeton.edu/ 
  * simulator: TORCS <br />
  * Deep learning tool: Caffe <br />
#### 2. "A plugin for GTAV that transforms it into a vision-based self-driving car research environment." <br />
  * link: https://github.com/ai-tor/DeepGTAV <br />
