# UyduHackLibrary


    import ephem
    import numpy as np
    from numpy import genfromtxt
    from pwn import *
    from itertools import islice
    from math import *
    from skyfield.api import EarthSatellite,load,Topos
    
# Simple Web App Scanner

    ██╗    ██╗███████╗██████╗ ███████╗ ██████╗ ██╗  ██╗
    ██║    ██║██╔════╝██╔══██╗██╔════╝██╔═══██╗╚██╗██╔╝
    ██║ █╗ ██║█████╗  ██████╔╝█████╗  ██║   ██║ ╚███╔╝ 
    ██║███╗██║██╔══╝  ██╔══██╗██╔══╝  ██║   ██║ ██╔██╗ 
    ╚███╔███╔╝███████╗██████╔╝██║     ╚██████╔╝██╔╝ ██╗
     ╚══╝╚══╝ ╚══════╝╚═════╝ ╚═╝      ╚═════╝ ╚═╝  ╚═╝ 
 
#Usage
        Usage: webfox.py [options]
        
#Options
        Options: -h, --help show this help message and exit
        -t TARGET_ADDRESS, --target=TARGET_ADDRESS (Enter domain)
        
#Example
        python webfox.py -t tesla.com
