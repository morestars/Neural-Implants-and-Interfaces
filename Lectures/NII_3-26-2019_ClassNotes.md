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
  * increases surface contact on a ____ level
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
  
  
  



