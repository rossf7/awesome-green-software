# Green Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Research, tools, code, libraries and training to for building applications that emit less carbon into our atmosphere.

An [awesome list](https://awesome.re) created and managed by the [Innovation Working Group](https://github.com/Green-Software-Foundation/innovation_wg) in the [greensoftware.foundation](https://greensoftware.foundation).

**Disclaimer**: This list is created for informational purposes only and any links do not constitute an endorsement, recommendation, or favoring by the Green Software Foundation, its member organizations or contributors to the list.

## Contents

- [Dev / Tooling](#dev--tooling)
    - [AI](#ai)
        - [Carbon](#carbon)
        - [Energy](#energy)
    - [Cloud based](#cloud-based)
        - [AWS](#aws)
        - [Azure](#azure)
        - [Google](#google)
        - [Multicloud](#multicloud)    
    - [Code based](#code-based)
    - [OS based](#os-based)
        - [Linux](#linux)
        - [Web](#web)
        - [Windows](#windows)
- [Organizations](#organizations)
- [Research / Articles](#research--articles)
    - [Research](#research)
        - [Artificial Intelligence](#artificial-intelligence)
        - [Computation](#computation)
        - [Data Centers](#data-centers)
        - [Emissions](#emissions)
        - [Programming Languages](#programming-languages)
        - [Streaming](#streaming)  
    - [Articles](#articles)

## Dev / Tooling

### AI

#### Carbon
- [Experiment Impact Tracker Library](https://github.com/Breakend/experiment-impact-tracker) Calculates carbon cost of ML job
- [scaphandre](https://github.com/hubblo-org/scaphandre) Power measurement (bare metal hosts, prometheus, within a docker container, etc)

#### Energy
- [Beaker (Allen Institue For AI)](https://beaker.org) Captures GPU power inside a container
- [carbontracker](https://github.com/lfwa/carbontracker) 
- [RAPL in Action: Experiences in Using RAPL for Power Measurements](https://www.researchgate.net/publication/322308215_RAPL_in_Action_Experiences_in_Using_RAPL_for_Power_Measurements)
- [Tool for tracking and predicting the energy consumption and carbon footprint of training deep learning models as described in Anthony et al. (2020)](https://arxiv.org/abs/2007.03051)

### Cloud based

#### AWS
- [Green Cost Explorer](https://github.com/thegreenwebfoundation/green-cost-explorer) A climate related spend analysis for AWS.

#### Azure
- [Microsoft Sustainability Calculator](https://appsource.microsoft.com/en-us/product/power-bi/coi-sustainability.sustainability_dashboard)

#### Google
- [Cloud Jewels](https://github.com/etsy/cloud-jewels)
  Blog: [Cloud Jewels: Estimating kWh in the Cloud](https://codeascraft.com/2020/04/23/cloud-jewels-estimating-kwh-in-the-cloud/)

#### Multicloud
- [Cloud Carbon Footprint](https://www.cloudcarbonfootprint.org/) An open-source cloud energy and carbon emissions measurement tool.

### code based
- [codecarbon.io](http://codecarbon.io/) Python : Track and reduce CO2 emissions from your computing
- [energyusage](https://pypi.org/project/energyusage/) Python : package that measures the environmental impact of computation. Provides a function to evaluate the energy usage and related carbon emissions of another function.  
- [carbontracker](https://github.com/lfwa/carbontracker) Python : Track and predict the energy consumption and carbon footprint of training deep learning models.

### OS based

#### Linux
- [FreeIPMI](https://www.gnu.org/software/freeipmi/) We can get the power consumption of a bare metal machine through the DCMI (IPMI extension).
- [ipmitool](https://github.com/ipmitool/ipmitool) We can get the power consumption of a bare metal machine through the DCMI (IPMI extension).
- [PoweerTOP](https://01.org/powertop) A Linux tool to diagnose issues with power consumption and power management.
- [turbostress](https://github.com/teads/turbostress) This tool generates load and outputs computer power metrics for this load.

#### Web
- [Carbonalyser - TheShiftProject](https://chrome.google.com/webstore/detail/carbonalyser/oblfkaonopplpldppkjdhnlcmkhgbcok)
- [Carbon Footprint of Sending Data](https://observablehq.com/@mrchrisadams/carbon-footprint-of-sending-data-around) An online calculator for estimating carbon emissions from network traffic, based on the Shift projects Lean ICT report.
- [Clickclean.org](http://www.clickclean.org/) Energy footprint of commonly used applications.
- [EcoGrader.com](https://ecograder.com/) An online website carbon estimator.
- [EcoMeter.org](http://ecometer.org/) Analyse the website ecodesign maturity.
- [GreenFrame.io](https://greenframe.io/onePage) Calculate Carbon Footprint of website.
- [GreenSpector](http://mobile-efficiency-index.com/en/)
- [Website Carbon Calculator](https://www.websitecarbon.com/) An online website carbon estimator.
- [WeDeex - Chrome](https://chrome.google.com/webstore/detail/wedeex/ojlagggckhpedblhemgjhecbggnibale)
- [WeDeex - Edge](https://microsoftedge.microsoft.com/addons/detail/wedeex/jbocoolinibenmobjadejejdbanalfee)

#### Windows
- [powercfg](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/powercfg-command-line-options)
  Blog : [Measuring Your Application Power and Carbon Impact](https://devblogs.microsoft.com/sustainable-software/measuring-your-application-power-and-carbon-impact-part-1/)
- [WeDeex](https://github.com/Wedeex-DevTeam/WedeexApp)
  Blog : [We need a Yuka for electricity to ease the energy transition](https://devblogs.microsoft.com/sustainable-software/we-need-a-yuka-for-electricity-to-ease-the-energy-transition/)

## Organizations
- [Climate Action Tech ](https://climateaction.tech)
- [Climate Change AI](https://www.climatechange.ai/)
- [Green Software Foundation](https://greensoftware.foundation)
- [SolarWind Foundation](https://solarimpulse.com/)
- [The Green Grid](https://www.thegreengrid.org/)
- [The Green Web Foundation](https://www.thegreenwebfoundation.org/)
- [TheShiftProject](https://theshiftproject.org/)
- [TimeForThePlanet](https://www.time-planet.com/fr)

## Research / Articles

### Research 

#### Artificial Intelligence
- [Energy and Policy Considerations for Deep Learning in NLP](https://arxiv.org/abs/1906.02243)
- [Energy-Efficient AI | Vivienne Sze | TEDxMIT](https://www.youtube.com/watch?v=Y0XGSnRrWiU&ab_channel=TEDxTalks)
- [Quantifying the Carbon Emissions of Machine Learning](https://arxiv.org/abs/1910.09700)
- [SECure: A Social and Environmental Certificate for AI Systems](https://arxiv.org/abs/2006.06217)
- [The AI Gambit — Leveraging Artificial Intelligence to Combat Climate Change: Opportunities, Challenges, and Recommendations](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3804983)

#### Computation
- [A Comparative Study of Methods for Measurement of Energy of Computing](https://www.mdpi.com/1996-1073/12/11/2204/pdf)
- [An experiment-driven energy consumption model for virtual machine management systems](https://hal.archives-ouvertes.fr/hal-01632962/document)
- [Quantifying the Carbon Emissions of Computation](https://arxiv.org/ftp/arxiv/papers/2007/2007.07610.pdf)

#### Data Centers
- [Architectural Tactics to Optimize Software for Energy Efficiency in the Public Cloud](https://github.com/so-vos/thesis/blob/main/Thesis_Vos_2021.pdf)
- [Balancing Power Systems With Datacenters Using a Virtual Interconnector](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7452537)
- [Carbon-Aware Computing for Datacenters](https://arxiv.org/abs/2106.11750)
- [Hiding Greenhouse Gas Emissions in the Cloud](https://www.nature.com/articles/s41558-020-0837-6)
- [Power consumption and efficiency of cooling in a Data Center](https://ieeexplore.ieee.org/document/5697800)
- [Supporting energy-awareness for cloud users](https://tel.archives-ouvertes.fr/tel-01973083/file/GUYON_David.pdf)
- [The Case for Energy-Proportional Computing](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/33387.pdf)

#### Emissions
- [A Framework For Collective Carbon Neutrality](https://www.carbone4.com/wp-content/uploads/2020/05/Carbone-4-NZI-Guidelines-Executive-Summary-april-2020.pdf)
- [Methodological Guide - Bilan Carbone (French)](https://www.associationbilancarbone.fr/wp-content/uploads/2018/03/bilan-carbone-v8-guide-methodologique-final.pdf)
- [Putting a CO2 figure on a piece of computation](https://ieeexplore.ieee.org/document/6128960)
- [The energy and carbon footprint of the ICT and E&M sector in Sweden 1990–2015 and beyond](https://download.atlantis-press.com/article/25860385.pdf)
- [The Most Important GHG Accounting Concept You May Not Have Heard of: The Attributional Consequential Distinction](https://ghginstitute.org/2021/04/21/the-most-important-ghg-accounting-concept-you-may-not-have-heard-of-the-attributional-consequential-distinction/)

#### Programming Languages
- [Energy Efficiency Across Programming Languages](https://greenlab.di.uminho.pt/wp-content/uploads/2017/10/sleFinal.pdf)
- [Google Apps: Energy Efficiency in the Cloud](https://static.googleusercontent.com/media/www.google.com/en//green/pdf/google-apps.pdf)
- [Green and Sustainability in Software Development Lifecycle Process](https://www.intechopen.com/chapters/69865)
- [GreenC5: An Adaptive, Energy-Aware Collection for Green Software Development](https://digitalcommons.du.edu/cgi/viewcontent.cgi?article=2122&context=etd)
- [Software development methodology in a Green IT environment](https://tel.archives-ouvertes.fr/tel-01724069/document)

#### Streaming
- [DImpact](https://dimpact.org)

### Articles
- [Assessing the suitability of the Greenhouse Gas Protocol for calculation of emissions from public cloud computing workloads](https://davidmytton.blog/assessing-the-suitability-of-the-greenhouse-gas-protocol-for-calculation-of-emissions-from-public-cloud-computing-workloads/)
- [Estimating the marginal carbon intensity of electricity with machine learning](https://www.tmrow.com/blog/marginal-carbon-intensity-of-electricity-with-machine-learning/)
- [How to incorporate carbon free energy for Google Cloud regions](https://cloud.google.com/sustainability/region-carbon)
- [How we’re making Dropbox data centers 100% carbon neutral](https://dropbox.tech/infrastructure/making-dropbox-data-centers-carbon-neutral)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
