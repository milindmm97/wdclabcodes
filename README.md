# wdclabcodes
.m files are matlab files for AWGN channels, Rayleigh. 
Also 2 more .m files for mrc and egc 

.mdl files are for simulation 
Perform theoritical and Monte Carlo Simulation
Theoritical Data point 0:1:12 
Monte Carlo Data point 1:3:12 
BER Variable = grayBER 
Sample time for all blocks = 0.001

EC1 and EC2 .cc are modified files for NS3 simulation
EC1 has 3 nodes 
EC2 has 4 nodes 

To perform simulation: 
./waf --run scratch/<filename _without_.CC>
make sure you are in /ns folder 
