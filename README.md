# Radical-Polyesters-ROCOP-Spacer-Conductivity
DFT outputs for TEMPO-functional radical polyesters: Gaussian 16 log files at ωB97X-D/6-311G(d,p)/CPCM level.

DFT outputs supporting the manuscript:
**"Radical Polyesters: Connecting Spacer Structure to Bulk Electrical Conductivity"**, 
K. G. Stakem, S. J. Cassidy, W. K. Myers, G. L. Gregory, _Submitted_, 2026.

## **Method**
All calculations performed with Gaussian 16 (Rev. C.01). Geometry optimisations at the ωB97X-D/6-311G(d,p) level of theory at 298 K, using the CPCM implicit solvent model (SCRF, modified dielectric: ε = 16, ε<sub>∞</sub> = 1.867 to mimic the epoxide monomer environment). Frequency calculations at the same level of theory confirmed optimised structures as true minima. NBO analyses were performed using the 'pop=NBO' keyword. Calculations were carried out on DP = 2 open-shell singlet diradical oligomer models for each P(GTEMPO-_alt_-anhydride) structure, considering head-to-tail connectivity and opposing stereocentre configurations.

## **Contents**
Gaussian 16 '.log' files for optimised structures of P(GTEMPO-_alt_-anhydride) DP = 2 oligomer models, organised by anhydride spacer:
- GA (glutaric anhydride)
- DGA (diglycolic anhydride)
- TDGA (thiodiglycolic anhydride)
- PA (phthalic anhydride)
- MPA (4-methylphthalic anhydride)
- HHPA (hexahydrophthalic anhydride)
- TCA (tricyclic anhydride)

Files include neutral diradical (TEMPO•/TEMPO•), singly oxidised (TEMPO⁺/TEMPO•), and doubly oxidised (TEMPO⁺/TEMPO⁺) states, with NBO outputs where relevant.

## **Contact**

Georgina L. Gregory — georgina.gregory@chem.ox.ac.uk, Chemistry Research Lab, Department of Chemistry, University of Oxford

## **Licence**

Released under the BSD 3-Clause Licence. See LICENSE file.
