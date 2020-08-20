## Research Summary <br>
Modelling heat and mass transfer characteristics in batch and flow reactors under non-isothermal conditions is critical while evaluating scaling-up the reactor sizes to achieve higher production rates.<br>
I present a test-case where we scale-up a flow reactor to manufacture 'NiBTDD' MOF from lab-scale (grams) to industrial scale (kilograms). <br>
- Tradeoffs associated with enlarging reactor tubes for higher production rate while losing benefits of small system dimension in the flow reactor must be judiciously considered before scaling-up the system.<br>
- The reactor tubing was modeled as a 2D axisymmetric geometry with varying diameters from 1/16 in (0.159 cm) to 2 in (5.08 cm), and a constant length of 8 m in the crystallizer (heated reaction zone of the tubing). To achieve a residence time of 60 min, a linear velocity of 13.4 cm/min and total flow rate of 0.267 mL/min was used.<br>
- A coupled heat transfer and fluid flow problem is solved using the nonisothermal flow interface. Laminar Flow (SPF) and Heat Transfer in Fluids (HT) modules are employed and boundary conditions at the inlet, outlet, for fluid flow and heat transfer are specified.<br>
- All cases engaged physics-controlled meshing sequence, which ensures there were no void regions in the computational domain or overlap in neighboring elements. The meshing sequence also resulted in low computational time and cost, while maintaining sufficient resolution with desired accuracy. <br>
- Thermal properties of individual components such as tube wall, the silicone oil phase, and the dispersed MOF precursor phase must be considered in the model and are analogous to electrical resistances in a circuit. <br>
- With regards to reaction driven crystallization processes, reaction rate (r), and reaction enthalpy (∆H¬R) must be considered in the model which strongly influence local temperature of reagents as they traverse along the heated reaction zone. <br>

---

### Scale-up Scenario to Manufacture 1 kg of NiBTDD per month:
- Based on our heat transfer models, in order to maintain favorable heat and mass transfer characteristics, the reactor configuration must have a maximum ID of 3/8 inch. However, this configuration can only achieve ~0.21 kgMOF per month, while the reactor with 1/16 inch ID used in the current study synthesizes ~0.00587 kgMOF per month, two order of magnitude lower. <br>
- A resourceful strategy in this case would be using a combinatorial approach of increasing tube ID to an extent where heat transfer characteristics are retained and parallelization of such reactor units, ensuring higher production rates. <br>
- Batch synthesis procedure used in the study employs 1000 mL glass bottle producing at ca. 100 mg scale and scaling-up the synthesis to manufacture 1 kg of Ni2Cl2(BTDD) would involve using ca. 1000s of identical reactors or a larger volume reactor, which may need re-optimization of reaction conditions due to poor translation of synthetic conditions with change in batch reactor volume.<br>

---

### 2D plots visualizing growth of thermal boundary layers <br>
<img src="images/HT1.JPG?raw=true"/>

<br><br>
---

### Physics controlled meshing sequence for different tube IDs <br>
<img src="images/HT2.JPG?raw=true"/>

<br><br>
---

### Axial temperature profile for reactors with different tube IDs and 3D slice plots showing thermal Boundary Layers <br>
<img src="images/HT3.JPG?raw=true"/>

<br><br>
---

### Production output as a function of reactor tube ID and Parallelization Scheme <br>
<img src="images/HT4.JPG?raw=true"/>

<br><br>
---
