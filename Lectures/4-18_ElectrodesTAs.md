# Electrodes
### Question on the exam
* why is it easier to depolarize long axon than small round cell
* conceptual question
* current moving from inside to outside, Vm across the membrane
* gradient is what's important
* no voltage gradient for small round cell
* no place for the current to go

### Microelectrode Array
### simtulation and recording
* what are the requirements of stimulation electrodes?
  * small
  * larger surface area to increase capacitance, charge injection
* recording electrodes

### Materials
* similar charge injection limits except for PEDOT
* avoid damage, don't need it too high
* little current draw for recording electrode

### Coating to improve performance
* Activated Ir oxide
  * changes faradaic interaction at electrode surface in body
  * higher capacitive charge injectin?
  * faradaic charge
* TiN
  * SA --> capacitive
* Carbon nanotube
  * capacitive
* PEDOT
  * low potential range --> capacitive
  * high range --> faradaic
* reversible faradaic interactions for these methods

### Microwire array
* microwire array
  * b) wet etching isotropic
  * d)
  * e) passivation, creates insulating layer
  * photolithography
    * bare Si wafer
    * SiO2
    * photoresist layer
    * mask over photoresist
    * Q7: positive --> material is exposed and etched away
    * negative -->
    * positive used in example
    * buffer oxide etching
    * Q8: SiO2 used to protect bc photoresistor is not chemically stable, cannot survive
  * wet etching
    * anisotropic - only vertical etching
    * isotropic - equap etching in viertical and horizontal directions
    * degree of anisotropic: know the formula
      * anisotropic == 1
      * isotropic == 0
    * xyz gives the orientation
      * break bonds requires energy
      * once you reach the 1 plane, it stops??
    * use KOH for anisotropic wet etching
      * why use hexagon?
      * need further etching to make round
      * even distribution of current density, to prevent damage at concentrated corners
    * flatter surface --> lower etching rate
    
### Isotrpic wet etching for tapering tip
* area close to tip will have longer chemical durations for slow dip change
* control dipping speed --> not really
  * need it to be computerized/automated
* dip it at an gnles

### Au deposition
* epavotarion is highley directional
  * can only more in one direction
  * shadow areas
* sputtering
  * conformal
  
### Parylene depolsition
* passivation/insulation
* stable gas
* don't want tip to be passivated
* treate tip with...

### Micromachined arrays
* Utah array
* mounted Al can corrode/melth through Si
* dopes the Si to p+
* create p-n junction to make it more stable
* slicing to mechanically remove material
* don't use etching because long distance/depths
* wet etching to round the squares

### Flexible arrays
* paper if interested

# Electrochemical Testing
### electrode-tisue interface
* model of interface
* doulbe-layer capactiance: charge that moves to the surface of the electrode, non-faradic
* faradaic has reversible and irreversible
  * reversible is when reaction products stick to surface
  * nonreversible, they diffuse away

### Redox reaction
* another form of the Nernst equation
  * chimcal gradient with electrical potential
* at som eq. voltage, have a given concentration
* shift away from eq, one concnetration dominates

### Potentiostat
* 2: ausilllary.counter/return path
* 3: reference local for baseline

### Cyclic Voltamettry
* injecting voltage
* onserving current being drawn
* cyclic bc returning to original state
* current profile
* plot current vs potential
* purely resistive interface --> linear I = V/R line
* purely capacitive --> square shape, height of bax proportional to rate of change of voltage
* scale is slow on time scale
* need to reach equilibrium to measure effective global changes
* current generated is porportional to rate of change of products
  * biggest at equilibrium point
* platinum shown
  * where the reaction occurs at a given voltage
  * don't want electrolysis
    * leads to corrosion and damage
  * range of voltage we can apply to electrode
  * curve sharply changes at edges due to electrolysis
    * water window
  * standard potential E^0
    * reference electrode has some voltage across it
    * need to factor it in
    * SHE - standard hydrogen electrode
    * SHE has 0.2V potential by convention
    * 0.5 scale is actaully measuring 0.7 V
    * standard potential allows for comparision against standard hydrogen
  * current injectin by area under/within curve
    * larger area == larger charge injection ability
* Activated Ir shown by graph with number of cycles used
  * more cycles --> higher curve, large area, more charge injection ability
* timescale is large, but stimulation pulses are short, reactions don't have enough time to reach
equilibrium, don't have enough time for charge buildup
* can use it measure electrode health
  * minor cracks and delamination
  * charge injection changes
  * irreversible interaction between pre (a) and post (b)
  
### Electrode Poteintal Measurement
* controlling v1 with voltage controlled system
* even if impedence doesn't change, current profile gives spikes, might cuase offtarget recruitment
* V3 is constant in current controlled system

* Voltage on electrod ewaveform
  * ohmic voltage
  * b) both
  * c) faradaic mostl
  * d) irreversible reactions, electrolysis, stays flat
  * wnat to get rid of (d)
  
* inject current pulses of same lenght, slowly increasing amplitude of injected current (measured/converted to charge density)
* (d) is shwon by plateau of curve
* takes ito accoutn length of stimulation pulse
  * advantage of CV
  
## Pulse clamp
* inject current pulse, turn it off, measure how much charge leaves capacitor
* measureing charge on the capacitor
* know how much charge was lost
* low current --> have not hit reversible, 
* high current --< reversible reaction, lose charge to reversible reaction

    

