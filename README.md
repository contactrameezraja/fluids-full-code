## Code provenance and data correction

This repository contains the **full computational code** developed for the MA9M4
Fluids Project on Poiseuille flow at the micro- and nano-scale.

During the initial stages of the project, the experimental comparison used the
slip-length values reported in **Whitby et al. (2008)**. While completing the
literature review, it was identified that these values were subsequently corrected
in **Whitby et al. (2009)**.

To ensure accuracy and transparency:
- The **original implementation using the 2008 data** is preserved for completeness. 
- A **revised implementation using the corrected 2009 slip lengths** is also included.
- All results and conclusions in the final report are based on the **corrected 2009 data**.

This approach preserves the full development history of the project while ensuring
that the final analysis reflects the most accurate experimental data available.


## Repository contents

- `poiseuille_whitby_2008.ipynb`  
  Original implementation using Whitby et al. (2008) slip-length data.

- `poiseuille_whitby_2009_corrected.ipynb`  
  Final implementation using corrected slip lengths from Whitby et al. (2009).
  This notebook corresponds to the results presented in the report.

