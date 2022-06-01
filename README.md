# _This repo is archived. See https://github.com/waggle-sensor/virtual-waggle_

# Virtual Waggle (VW)

#### Lead: Sean Shahkarami

### Overview:
VW is a software-only programming environment for building and testing edge computing code for the Waggle framework.  Nearly everything that can be done on a Real Waggle, should be possible on a VW - physical cameras, sensors, and an attached WagMan board are not required.  The VW can be given to students or hosted in the cloud to help foster quick development of edge computing components.  By spawning thousands of VWs, the scalability of the data repository and management tools can be tested.  A wide range of inputs could be tested via VW.

### Goal:
VW will be easy to download, run, and test.  It will include a variety of edge run-time environments, such as TensorFlow Lite, OpenCV, and PyTorch.

### Use Cases:
#### Getting Started:
* Find documentation on how to download or run VWs in the cloud
#### Launch a VW and test Edge-model:
* On Chameleon, SDSC machine, or local laptop with VW installed, launch a VW.
* Try example Edge Model packaged with VW.
* Pull newly developed Edge Model (see CTSS) from external source and run it.
* Check that Waggle Plugins sent correct data to the test Beehive.

### Milestones:
* Publish design document, including container/VM evaluation
* Deploy initial prototype into continuous integration on Chameleon
* Test V1.0 in production with auth tokens
* Release VW V1.0 with tutorials and examples

### Implementation Notes:
The Virtual Waggle capability is provided by the Waggle software stack, and can be obtained from [waggle-node](https://github.com/waggle-sensor/waggle-node) repository. Please follow the link to discover and use VW features. 
