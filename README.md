# Sensing Driven Micro Sleep Cycles (ISAC)
The ISAC enabled cell tower safely puts specific PAs and Massive MIMO antenna arrays into sub-millisecond sleep modes when no objects or UEs are present.

## Challenge
* The primary challenge with __drone tracking__ is the highly dynamic nature of the target:</br>
  Drone speeds require fast Doppler processing, and abrupt changes in trajectory require a tightly bounded sleep calculation loop to avoid track loss.

## Simulation environment for testing
* Simulator environment: NS3, USRP SDRs
* To integrate sensing-driven micro-sleep for drone tracking into both NS-3 (for network-wide macro modeling) and USRP SDRs (for physical over-the-air validation), 
the software and hardware stacks must be structured to support both monostatic and multistatic coordination as well.
