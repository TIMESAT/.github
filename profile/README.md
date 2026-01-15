# TIMESAT Official GitHub

Welcome to the **official GitHub organization for TIMESAT**.  
This is the **only official repository hub** for the TIMESAT software and related resources.

## About TIMESAT
TIMESAT is a software package for analysing time-series of satellite sensor data. We have developed TIMESAT to be able to investigate the seasonality of satellite time-series data and their relationship with dynamic properties of vegetation, such as phenology and temporal development. The temporal domain holds important information about short- and long-term vegetation changes. The first generation of TIMESAT - distributed as version 3, was limited to processing of data with a regular time step, typical of data from MODIS or NOAA AVHRR. This version is very stable and is still distributed at the timesat webpage, see Contact. The new generation, named TIMESAT version 4 and distributed in this repository, is built on the same principles but works with irregularly spaced data in time (Sentinel-2, Landsat etc.) and has several incremental modifications and improvements. TIMESAT 4 is the basis of several operational products, e.g. Copernicus CLMS phenology data for Europe from Sentinel-2 data ([HR-VPP](https://www.copernicus.eu/en/access-data/copernicus-services-catalogue/high-resolution-vegetation-phenology-and-productivity)) and the globe from Sentinel-3 data (CGLOPS), and projects by ESA ([RAMONA](https://www.ramona.earth/), [SEN4LDN](https://esa-sen4ldn.org/en)).

## License & Usage Notice


**The TIMESAT algorithmic core is proprietary software.**

It is freely available for **non-commercial scientific research,
academic teaching, and personal use only**.

**Commercial use of the TIMESAT core requires a separate written agreement with the authors.**

The TIMESAT organization also provides **open-source tools and interfaces**
(including graphical and command-line applications) that facilitate
scientific use of the TIMESAT core.

Detailed license terms are provided in the individual repositories
(e.g. `timesat`, `timesat-engine`, `timesat-gui`, `timesat-cli`).

## Featured Repository
👉 [TIMESAT-GUI](https://github.com/TIMESAT/TIMESAT-GUI)  
This repository provides the **official Python implementation of TIMESAT**.  
It contains the core functionality, documentation, and examples for working with satellite time-series data in Python.

## Repositories
All official code, documentation, and updates related to TIMESAT will be published under this organization.  
Please verify that any TIMESAT-related repository is hosted here to ensure authenticity.

## Contact
For more information about TIMESAT, distribution of TIMESAT version 3, and commercial licensing inquiries, please refer to the official website:  
👉 [TIMESAT Website](http://web.nateko.lu.se/timesat/timesat.asp) or email us: zhanzhang.cai@nateko.lu.se

## Quick start
Install TIMESAT-GUI:
```bash
pip install timesat-gui
```
After installation, start the TIMESAT-GUI with:
```bash
timesat-gui
```

## Citation
If you use **TIMESAT** or **TIMESAT-GUI** in your research, please cite the corresponding release on Zenodo:
> Cai, Z., Eklundh, L., & Jönsson, P. (2025). *TIMESAT4:  is a software package for analysing time-series of satellite sensor data* (Version 4.1.x) [Computer software]. Zenodo.   
> [https://doi.org/10.5281/zenodo.17369757](https://doi.org/10.5281/zenodo.17369757)

## History and Origins

The TIMESAT software was first formally described and introduced
in the scientific literature in 2004 (Jönsson & Eklundh, 2004),
providing a robust framework for analysing time-series of satellite
sensor data. This foundational work established the theoretical and
methodological basis for extracting seasonality and phenological
metrics from vegetation index time series and has since been widely
used in both research and operational applications.

The original idea for TIMESAT emerged from interdisciplinary
discussions between Professor Per Jönsson (applied mathematics and
signal processing) and Professor Lars Eklundh (vegetation remote
sensing and ecology). Informal conversations—famously while
accompanying their children at a playground sandbox—highlighted
the need for a mathematically grounded, ecologically meaningful
approach to satellite time-series analysis.

Since its first formalisation in 2004, TIMESAT has evolved through
multiple generations, and version 4 represents its current,
widely adopted implementation. For full details on the original
methodology, see:[**Jönsson & Eklundh, 2004.**](https://www.sciencedirect.com/science/article/pii/S0098300404000974)
