### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

There is no absorption process since tefibazumab was administered intravenously.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

The standard lymph and fluid recirculation flow rates and the standard vascular properties of the different tissues (hydraulic conductivity, pore radii, fraction of flow via large pores) from PK-Sim were used ([Niederalt 2018](#5-references)).

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

The FcRn mediated clearance present in the standard PK-Sim model was  used as only clearance process. The standard physiological parameters related to FcRn mediated clearance were used (rate constants for endosomal uptake and recycling, association rate constant for FcRn binding and concentration of FcRn in the endosomal space) ([Niederalt 2018](#5-references)).

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

The Kd(FcRn) was fitted to the experimental plasma concentrations.

| Model Parameter | Optimized Value | Unit |
| --------------- | --------------- | ---- |
| `Kd(FcRn)`      | 0.85            | µM   |

