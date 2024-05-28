# improved_rman_script
# This script will utilize new rman features present in 11gR1-12cR2.
# This script aims to be dynamic and can vary configurations per server, some of the configuration that can be dynamic is prallelism vs. CPU. 

#Continued on May 28, 2024
The issue on the current rman script is that is not able to scale up and features can't be turned off or on without so much modification. 
Aiming to simplify the rman backup. 
