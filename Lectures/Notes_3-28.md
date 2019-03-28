# NII Notes from 3/28

## Formal stimulation analysis
* where do the ions go to create an AP?
  * Frank Rattay
  * IEEE TBME '86, '89
* neural stimulation affects different parts of the axon differently
  * activating funciton from ABE class
* current goes across membran
* current also moves along the axon length
  * inside axons and outside axon
* Vn is the change in membrane potential
* dVn/dt function
  * same thing as above in the slides, just reordered variables
* incorporate membrane diameter into equation
  * Ga and Cm will be affected
  * Cm depends on surface area of axon
* multiply by Δx/Δx
  * distribute the (Δx)^2
  * creates an expression for extracellular voltage w/o intracellular voltage
  * second spatial derivative
    * activating function = ∂...
* i_ionic,n accounts for the previous HH parameters done in HW2

## Extracellular voltage calculation
* i = I_el / (4πr^2)
* account for distance in z and r

## Activation function
* second derivative of extracellular voltage
* shows what happens to the membrane potential at different points along the axon
* current flow out at the center --> depolarization
* current flow in around the center --> hyperpolarization
* small, short neruons will be hard to depolarize

## Cathodic 
* pulls positive ions from the outside
* depolarization  near the center
* voltage difference between points within the axon along its length
* minimal voltage difference along the radial width of the axon will not create current
* electrode closet to axon or use a stronger magnitude pulse
  * harder to get enough membrane change along the length when far away
  * too close, there will be too much hyperpolarization flanking regions
    * probably actually that there is such a wide depolarization range that there is little 
    difference in voltage along its length because you need 
    
## Anodic
* reverse effects of close vs near
* require greate amplitudes to illicit action potentials

## Cathodic vs Anodic
* figure in slides

## Strength Duration Curve
* minimum parameter values needed to evoke an AP
* rheobase: 
* chronzxie:
  * approximately the minimum energy needed to depolarize neuron
* threshold for evoking an action potential

## Large axons respond to lower stimulation amplitudes
* C fiber is smaller
* A-B fiber is larger

## Electrical simtuation reverses 'normal' muscle recruitment order
* larger muscles require larger axons to innervate them
  * physiological parameter
* small motor units are recruited first in normal physiology
* electrical recruitment activates large axons first, not small axons
* loss of fine motor control in neural stimulation

## Amplitude effect on neural targeting
* target radius from the electrode
* radius is proportional to the square root of the intensity
* recruitment: neurons that are responding to stimulation

## PUlse duration effects on neural targeting
* increase pulse duraiton at a given amplitude
* recruitment region remains constant
* number of neurons recruited will change
  * increases for longer durations
  
    
