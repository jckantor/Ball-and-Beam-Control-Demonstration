Ball and Beam Control Demonstration
===================================

*Ball and Beam Control Demonstration* is an interactive demonstration of feedback control for a ball and beam system. It was written in Matlab to demonstrate proportional and proportional-derivative control in the classroom and for homework exercises. It was originally written in 2001, and revised in 2011 for the then-current version of Matlab. The github repository was created in 2015.

<img align="center" src="https://raw.githubusercontent.com/jckantor/Ball-and-Beam-Control-Demonstration/master/ballbeam.png" alt="Ball and Beam Screenshot" title="Ball and Beam"/ width="320"  >

### Installation

The demonstration is completely self-contained in a single Matlab function. Download the file by clicking on this [link](https://raw.githubusercontent.com/jckantor/Ball-and-Beam-Control-Demonstration/master/ballbeam.m) and saving to your Matlab directory with the name `ballbeam.m`.  

Alternatively, you can download the whole project as a `.zip` file from [github](http://jckantor.github.io/Ball-and-Beam-Control-Demonstration/) or [Matlab Central](http://www.mathworks.com/matlabcentral/fileexchange/151-ball---beam-demo). Unpack and place the resulting folder in your Matlab directory. 

### User Interaction

The `ballbeam.m` file is a function that can be run with no arguments. Start the demo by entering `ballbeam` at the Matlab command prompt.

    ballbeam

The demo starts up in manual mode. The vertical slider moves the end of the beam up and down. The bottom slider adjusts the setpoint indicated by the red marker. Push the `Run` button to start the simulation. The ball will roll back and forth on the beam as you move the beam position up and down. The simulation is stopped by pushing the |Stop| button or when the ball rolls off either end of the beam.

A summary of the simulation results is shown in a figure window when the application is closed.

## Dynamics
 
 (http://nbviewer.ipython.org/github/jckantor/Ball-and-Beam-Control-Demonstration/blob/master/Dynamics.ipynb)
