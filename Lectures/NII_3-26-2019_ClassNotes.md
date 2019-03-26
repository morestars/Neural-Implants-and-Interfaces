# Class Notes form 3/26/2019
## Neural Stimulation
### Starts on Electrodes slide
#### Electrodes
* Electrodes are the same as recording with stimulation
* Corrosion is more of a concern
#### Stimulation
* Charged particles moving around
  * Ions in body
  * Electrons in technology
#### Electrical current propagates through ion flow
#### Electrical current flow causes ions to move towards the electrodes
* positive ions to negative electrode (cathode)
* negative ions to the positive electrode (anion)
#### Battery in a cup of water
* bubbles --> hydrolysis
#### Long duration current flow causes electrochemistry
* Ions jump accross??
#### Short duration current flow does not cause electrochemical reactions
* Just long enough to attract and repel ions
#### We dont want to do electrochemisstry in the body
* IPG - implantable pulse generator
  * need pulse to avoid electrochem rxns
* Biphasic pulse to account reset ions
  * Area under the curve is wat matters
#### Current or Voltage?
* Current: Q = I * t
* Avoid harm to body
#### Different pulses used for electrical stimulation
* review paper of safety considerations for pulsatile techniques
  * by Merryl, will be put up on blackboard
  * mechanisms of safety factors
* monophasic pulse
  * no return current
  * effective response illicitation
  * tissue damage high
* charge balanced biphasic
  * no damage
  * not effective for neurons to fire AP
  * too fast for neurons to respond to change in local ion concentrations
* charge balanced biphacis with delay
  * industry standart
  * phases deparated with dead space
    * cathodic phase and???
  * corrosion is still an issue
  * charge is how many electrons are there --> area under the curve
#### Interface equivalent circuit
* __check positive current and voltage direction__
* I = C dVc/dt
* Jumping electrons across interface --> Faradaic charge injection
* What influences Z?
  * Solution chemistry
  * Electrode material
  * Reactive materials may cause electrochemistry sooner than others
* What influences C?
  * Surface area
  * Electrode acts as capacitor
  * Larger SA, more electrons on in, increase capacitance
#### Goal for electrode design is to deliver pulses with NO FARADAIC reactions
* charge injectin capacity (Q_inj)
  * amount of charge per unit area that can be delivered through an electrode without causing water elecrolysis
  * Pt electrodes --> ~300 uC/cm^2
* Platinum black
  * makes a 3D contact area to increase capacitance
* PEDOT
  * increases surface contact on a __?__ level
* Surface roughening
* Activated irridium
  * more irridium from one state to another (III <--> IV)
  * electrode does electrochemistry
  * specific electrochemistry that can be reversed
#### How can you find Rs, Z, C?
* Cochlear implant given
* For current to flow, a potential difference is needed
* Small electrode close to neurons
  * High current density
* Large return electrode
  * Low current density
  * Same overall current though
  * Order of magnitude larger than small electrode
  * Allows for approximation given by second circuit diagram
    * Electrochemistry methods used in practice by electrode designers use more refined solutions
* Current pulse given
  * What does V look like?
  * Ic = C*dVc/dt
  * Vc = 1/C * integral(
  * Vc = 1/C * I * t
  * Linear increase at high, steady current
  * Stays constant while current is zero in middle
  * Linear decrease while current is low
  * Big electrode, small voltage
  * Smalle electrode, big voltage slope
* Z = inf, R is small, but nonzero
  * Voltage drop is entirely over Rs at the initial spike in current
  * C charges at high, steady current
  * Initial voltage spike is conserved when folrage drops suddently at top of curve
  * Vr = I*Rs
* Z = inf, R is large
  * Exaggerated version from before
* Z != inf
  * Faradaic charge transfer
  * Short over C initially, so voltage drop entirely over Rs
#### In-call problems
* Z?
  * Z = inf
* C = 66 nF
* Rs = 6 kOhm
* pits
  * increase SA
  * increase C
  * flatter change in voltage region while current is high-steady, and low-steady
* Faradaic reactions
  * obtuse angles become curved
  * ~~clean vertical lines at current onset become curved~~
  * does not channge Rs, so still reaches -1.2 in a vertical fashion
#### How does a pulse affect the neuron?
* first phase
  * cathodic pulse
  * negative charges attract positive ions
  * fewer positive ions next to neuron
  * Vm depolarizes locally (gets more positive in relation to ECF)
  * hyperpolarization on the sides (rmbr Applied Bioelectrics)
* How much current is actually flowing near the neuron?
  * I = 4*pi*r^2*i
  * i = I / (4*pi*r^2) uA/patch area
#### How is the stimulation current affected with added scare formation onthe electrode?
* same for a current driven pulse
* does not change due to scar formation
* scar formation is bad for recording, less so far stimulation
* voltage pulse?
  * current goes down with increase scare tissue impedence
  * decreased ability to stimulate neuron
#### How does the pulse eboke an AP?
* Typical pulses are 100-500 us in duration
* graph in seconds --> increases by 1 ms for each step
* all of the current conducted through Cm
#### What is the approximate change in membrane potential delVm?
* 100 uA pulse
* 100 us
* electrode is 1 mm away
* trying to get order of magnitude here
* d = 10 um fiber
* L = 2.5 um node of Rnavier length
* SA = pi * d * L = 78 um^2
* Cm = 
* i = 0.00062 uA
* delVm = 82 mV
 
  
  



