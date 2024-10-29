# bestOfDimensionslessNumbers
## Heat transfer

#### Fourier / Graetz number
- is my transient process thermally converged?
- if not, what is the temperature differential in degrees celsius?
- can my melt stream be thermally controlled by the walls?

####  Nahme number
-  is my rheological measurement affected by viscous dissipation?
  
#### Biot number 
- is my thin sheet/film/tube etc. thermally homogenous?
  
## Viscosity and viscoelasticity

#### Deborah number
- essentially asks 'does the transiently-upset material remember its previous state?'
- compares relaxation time and residence time ('process time') in a transient process
- can be used to analyse layer adhesion in coextrusion [1]
- applicable to a parcel of viscoelastic material (think melt travelling through the relaxation zone of a die at a constant shear rate)
- if the parcel is relaxed, expect it to behave like a Newtonian fluid
- note that for a sufficiently long relaxation zone / sufficiently low shear rate, the very long residence time dominates and distinction of materials of different relaxation times is quite difficult
- Cannot be used to look a the upset itself, for that we have the .... 
  
#### ...deformational-relaxational Weissenberg number
- essentially asks 'when upsetting the material, what kind of response do I get?'
- compares relaxation time to a certain instantaneous rate(!) of deformation
- interestingly, with rising shear rates in steady-state shear, elastic-driven normal stresses almost always outgrow viscous shear stresses (see definitions of first normal stress difference and viscosity respectively). Hence the Weissenberg number can also indicate the ratio of shear and normal stresses / the ratio of elastic and viscous stresses.
- might indicate where am I on the viscosity curve of my steady-state-process
  
#### stress-ratio (the not-Weissenberg number - see Appendix 1 for naming problems)
- Simply compares elastic-driven normal stresses to viscous shear stresses
- Indicates whether normal stresses are relevant to our problem
- Care must be taken when using this stress ratio - it does not relate to any property of the material (no relaxation time in it!)

## Others

#### Manas-Zlocower index
-  is my flow shear- or elongation-dominated?

####  elongational parameter epsilon from PTT models
-  how strong can the normal stresses become?

#### Inertial number I
- will my pellet flow choke?

## Literature: 
[1] Morris, Barry A.: Troubleshooting coextrusion film problems by considering process–property relationships. In: Journal of Plastic Film & Sheeting Vol. 29 (2013), No. 2, p. 189–203 - DOI: 10.1177/8756087912473299

## Appendix 1 : Naming problems
See the 'Official Nomenclature of US and European Societies of Rheology' and the bulletin on 'Weissenberg and Deborah Numbers – Their definition and use' for more details.
