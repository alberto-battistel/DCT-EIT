# DCT-EIT
This algorithm for electrical impedance tomography (EIT) enhances image reconstruction by incorporating structural priors from other morphological imaging methods. Moreover, the algorithm comes with accompanying datasets that can be used to test its efficacy.

The algorithm is developed and tested using Matlab® 2019b with the *Eidors* toolbox (*https://eidors3d.sourceforge.net/*). The demonstration data includes:
- a forward model (generated by *Netgen*);
- an inverse model (generated by *Netgen*);
- a demonstration voltage measurement of the fully ventilated lungs
- a structural prior

If you use the DCT-based algorithm or our dataset (fully or partially), you must cite the following publications:
- Chen R, Krueger-Ziolek S, Lovas A, Benyó B, Rupitsch SJ, Moeller K (2023) Structural priors represented by discrete cosine transform improve EIT functional imaging. PLoS ONE 18(5): e0285619. https://doi.org/10.1371/journal.pone.0285619

In addition, as *Eidors* toolbox and *Netgen* are used in our algorithm, you must also cite the following publications:
- A. Adler and W. R. Lionheart, ‘Uses and abuses of EIDORS: An extensible software base for EIT’, Physiol. Meas., vol. 27, no. 5, p. S25, 2006. doi: 10.1088/0967-3334/27/5/S03
- J. Schöberl, ‘NETGEN An advancing front 2D/3D-Mesh generator based on abstract rules’, Comput. Vis. Sci., vol. 1, no. 1, pp. 41–52, 1997. doi: 10.1007/s007910050004


Copyright 2019 Province of British Columbia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
