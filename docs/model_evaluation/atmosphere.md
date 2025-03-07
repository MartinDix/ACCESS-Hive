
# MED: Atmosphere

{% include "call_contribute.md" %}

## [ESMValTool][esmvaltool-web]  {{ recom }}

[**Documentation**][esmvaltool-doc] |
[**Tutorial**][esmvaltool-tutorial] | 
[**Source Code**][esmvaltool-source]

ESMValTool is a community-developed climate model diagnostics and evaluation software package, driven both by computational performance and scientific accuracy and reproducibility. ESMValTool is open to both users and developers, encouraging open exchange of diagnostic source code and evaluation results from the Coupled Model Intercomparison Project CMIP ensemble. For a comprehensive introduction to ESMValTool please visit our documentation page.

## [METPLUS][metplus-web]  {{ recom }}

[**Tutorial**][metplus-tutorial]

METplus is a verification framework that spans a wide range of temporal (warn-on-forecast to climate) and spatial (storm to global) scales.  It is intended to be extensible through additional capability developed by the community. The core components of the framework include MET, the associated database and display systems called METviewer and METexpress, and a suite of Python wrappers to provide low-level automation and examples, also called use-cases.  METplus will be a component of NOAA's Unified Forecast System (UFS) cross-cutting infrastructure as well as NCAR's System for Integrated Modeling of the Atmosphere (SIMA).

METplus is being actively developed by NCAR/Research Applications Laboratory (RAL), NOAA/Earth Systems Research Laboratories (ESRL), NOAA/Environmental Modeling Center (EMC), and is open to community contributions.

### METplus Components  {{ recom }}

Links to the code repository and documentation for each METplus component are provided below:

- METplus Wrappers: [sources][METplusWrappers-source] | [docs][METplusWrappers-doc]
- MET: [sources][MET-source] | [docs][MET-doc]
- METviewer:  [sources][METviewer-doc] | [docs][METviewer-source]
- METexpress: [sources][METexpress-doc] | [docs][METexpress-source]
- METplotpy: [sources][METplotpy-doc] | [docs][METplotpy-source]
- METcalcpy: [sources][METcalcpy-doc] | [docs][METcalcpy-source]
- METdatadb: [sources][METdatadb-doc] | [docs][METdatadb-source]


## [PCMDI Metrics Package (PMP)][pmp-doc]  {{ recom }}

[**Documentation**][pmp-doc] | 
[**Sources**][pmp-source]

The PMP is used to provide “quick-look” objective comparisons of Earth System Models (ESMs) with one another and available observations. Results are produced in the context of all model simulations contributed to CMIP6 and earlier CMIP phases. Currently, the comparisons emphasize metrics of large- to global-scale annual cycle and both tropical and extra-tropical modes of variability. Ongoing work in v1.x development branches include established statistics for ENSO, MJO, regional monsoons, and high frequency characteristics of simulated precipitation.



[esmvaltool-web]: https://www.esmvaltool.org/
[esmvaltool-doc]: https://docs.esmvaltool.org/en/latest
[esmvaltool-tutorial]: https://esmvalgroup.github.io/ESMValTool_Tutorial/index.html
[esmvaltool-source]: https://github.com/ESMValGroup/ESMValTool#readme

[metplus-web]: https://dtcenter.org/community-code/metplus
[metplus-tutorial]: https://dtcenter.org/community-code/metplus/online-tutorial
[METplusWrappers-source]: https://github.com/dtcenter/METplus
[METplusWrappers-doc]: https://metplus.readthedocs.io/en/latest/
[MET-source]: https://github.com/dtcenter/MET
[MET-doc]: https://met.readthedocs.io/en/latest/
[METviewer-doc]: https://github.com/dtcenter/METviewer
[METviewer-source]: https://github.com/dtcenter/METviewer
[METexpress-doc]: https://metexpress.readthedocs.io/en/v4.4.2/
[METexpress-source]: https://github.com/dtcenter/METexpress
[METplotpy-doc]: https://metplotpy.readthedocs.io/en/latest/
[METplotpy-source]: https://github.com/dtcenter/METplotpy
[METcalcpy-doc]: https://metcalcpy.readthedocs.io/en/latest/
[METcalcpy-source]: https://github.com/dtcenter/METcalcpy
[METdatadb-doc]: https://metdatadb.readthedocs.io/en/latest/
[METdatadb-source]: https://github.com/dtcenter/METdatadb

[pmp-doc]: http://pcmdi.github.io/pcmdi_metrics/index.html#
[pmp-source]: https://github.com/PCMDI/pcmdi_metrics
