# Magnetic Loop Antennas for HF
======

## Introduction:

**TL:DR**:High efficiency/portability in exchange for very narrow bandwidth (a blessing in disguise, though for noisy environments)

## Parts:

### General Anatomy:

           Capacitor
             _| |_
          .-' | | '-.
        .'           '.
       /               \
      ;                 ;
      |   Inner Loop    |
      ;       .-.       ;
       \     (   )     /
        '.    '-'    .'
          '-._____.-'
  
          Outer Loop

* Adjustable Capacitor ~100pF or more
  * I've been told a "trombone style" capacitor is very effective if I need
    to homebrew it.
* Large diameter Copper Tubing (larger is more efficient)
* Coupling Loop
* Tripod or Other Stand

### Specific Parts

I used 20 feet of pipe from a local plumber supply. I chose 3/4" diameter
because it was the optimal amount for my budget, including a coupler ($40)

The capacitor was homebrewed and is in another directory.

The antenna bracket is to hold the loop against a plank of wood that will also
brace the inner loop.

## References:

This guy has used his mainly on 40m
http://home.alphalink.com.au/~parkerp/projects/projmag.htm

http://www.w0btu.com/magnetic_loops.html

http://www.hlmagneticloopantennas.com/

https://www.youtube.com/watch?v=Cv_RnLpZ9gw
Note:
  3m copper tubing w/ 19mm diameter
  Mentions vacuum-variable and high-power transmitting variable capacitor
  Suggests that 5m lengths would be more ideal (why?)
  


### Interesting Side Note:
One common frustration with magnetic loop antennas is the need to constantly
re-tune the antenna for every major frequency change.

Here are some interesting solutions/workarounds that address the
constant-tuning demand:

###Auto-tuning with Arduino:
//www.youtube.com/watch?v=oXc1oIbjXzwripod

###IR control:
https://www.youtube.com/watch?v=b3hUpQvO38k
