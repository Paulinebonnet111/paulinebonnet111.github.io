Hey, welcome on my personal page ! <br />

Feel free to leave comments and contact me for any sort of reason : 

<a href="https://www.linkedin.com/in/pauline-bonnet-phd-326b7084/" target="_blank"><img src="png/linkedin.jfif" alt="drawing" width="20"/>
<a href="https://www.researchgate.net/profile/Pauline-Bonnet-2?ev=hdr_xprf" target="_blank"><img src="png/research_gate.jfif" alt="drawing" width="20"/>
<a href="https://scholar.google.com.ar/citations?user=Scve-3UAAAAJ&hl=de&oi=ao" target="_blank"><img src="png/google_scholar.jfif" alt="drawing" width="20"/>

<!--  ( [Linkedin profile](https://www.linkedin.com/in/pauline-bonnet-phd-326b7084/) -->


## CURRENTLY

Looking for a new work opportunity in Marseille as a Projet Manager or Science Communicator in an ambitious projet related to Climate Sciences.


## WORK EXPERIENCES

### Postdoc in Atmospheric modelling and Machine Learning
February 2022 - April 2026
Affiliation: Prof. Veronika Eyring's group <a href="https://www.pa.op.dlr.de/~/VeronikaEyring/index.html" target="_blank">https://www.pa.op.dlr.de/~/VeronikaEyring/index.html</a>, Institut of Atmospheric Physics, DLR, Wessling (close to Munich), Germany.

This position is funded by the <a href="https://www.usmile-erc.eu/dlr/" target="_blank">ERC Synergy Grant USMILE</a>, and the <a href="https://ai4pex.org/" target="_blank">EU Horizon Europe Projet AI4PEX</a>,

 Abstract

In climate model development, “tuning” refers to the important process of adjusting uncertain free parameters of subgrid-scale parameterizations to best match a set of Earth observations, such as the global radiation balance or global cloud cover. This is traditionally a computationally expensive step as it requires a large number of climate model simulations. This step also becomes more challenging with increasing spatial resolution and complexity of climate models. In addition, the manual tuning relies strongly on expert knowledge and is thus not independently reproducible. To reduce subjectivity and computational demands, tuning methods based on machine learning (ML) have become an active research subject. Here, we build on these developments and apply ML-based tuning to the atmospheric component of the Icosahedral Nonhydrostatic Weather and Climate Model (ICON) at 80 km resolution. Our approach follows a workflow similar to other proposed ML-based tuning methods: (1) creating a perturbed parameter ensemble (PPE) of limited size with randomly selected parameters, (2) fitting an ML-based emulator to the PPE to generate a large emulated ensemble with the emulator, and (3) shrinking the parameter space to regions compatible with observations using a method inspired by history matching. However, in contrast to previous works, we apply a sequential approach: the selected set of tuning parameters is updated in successive phases depending on the results of a sensitivity analysis with Sobol indices. We tune for global radiative properties, cloud properties, zonal wind velocities, and wind stresses on the ocean surface. With one iteration of this method, we achieve a model configuration yielding a global top-of-atmosphere net radiation budget in the range of [0, 1] W m−2, and global radiation metrics and water vapour path consistent with the reference observations. Furthermore, the resulting ML-based emulator allows us to identify the parameters that most impact the outputs that we target with tuning. The parameters that we identified to be mostly influential for the physics output metrics are the critical relative humidity in the upper troposphere and the conversion coefficient from cloud water to rain, influencing the radiation metrics and global cloud cover, together with the coefficient of sedimentation velocity of cloud ice, having a strong non-linear influence on all the physics metrics. The existence of non-linear effects further motivates the use of ML-based approaches for parameter tuning in climate models.

- Creating a workflow to run ensembles of the ICON model simulations
- Selection and tuning of physical Parameters
- Implementation of a machine learning based tuning method using history matching (python and C++ language)
- Selection of reference datasets: observation and manually tuned previous model version 
- Adjusting the method to fit physics and dynamics output metrics.   
- Setting up a modelling regional modelling framework for predictions of renewable energy production 

### PhD in Mechanical Modelling of the Source of Glacial Earthquakes in Polar Region
Octobre 2017 - June 2021 <br />
Affiliations : Seismology team of IPGP, Centre des Matériaux of Mines ParisTech, PIMM laboratory in ENSAM, Paris, France

  Evaluating glacier mass loss is a current concern to understand the rapid evolution of ice caps related to climate change. 
  Iceberg calving is responsible for an important part of mass loss occurring at the front of marine-terminating glaciers in Greenland. 
  Some just-calved thin icebergs are unstable : during capsize, a force is applied to the terminus and is transmitted to the solid earth. 
  Therefore, a long-period (20s- 100s) seism is generated and seismic signal can be recorded by local and global stations. 
  The emitted seismicity contains precious information about the source mechanisms involved during the calving process.

A versatile mechanical modelling of iceberg capsize has been developed by A. Sergeant et al. . 
  Seismic signals provides constraints on the model and enables the calculation of the iceberg volume and its source dynamics. 
  This model has been first tested on two particular events at the Helheim glacier, Greenland (25 July 2013 at 03:13 UTC and 31 July 2013 at 19:31 UTC) 
  and the results are consistent with the iceberg volume measured separately using images available for this event. 
  Following the work of Amandine Sergeant, a first objective of this PhD is the development and validation of the mechanical model 
  (1) with the validation of the modelling of interaction between the iceberg and the surrounding ocean and 
  (2) with the extension of the modelling to the whole system which account for frictional force between the glacier and the bedrock. 
  A second objective of the PhD is to constrain the mechanical model with seismic signals from events of the last twenty years to evaluate 
  Greenland glacier’s mass loss by icebergs capsize and calving.

- Analysis of glacial earthquakes and inversion of the source force in obspy and Fortran 90: estimating ice losses due
to iceberg capsize
- Modelling iceberg capsize in free ocean: validation and improvement of a semi-analytical model in Python
- Hydrodynamic effects during capsize using CFD simulations: collaboration with LHEEA, Centrale Nantes
- Improvement and validation of a finite element model (Zset) for a viscous glacier with various basal friction laws
- Multiparameter analysis of the response of a tide-water glacierto the capsize of an iceberg: glacier model
constrained with GPS data
- Helheim glacier response to iceberg capsize: collaboration with AWI, Bremerhaven

PhD Advisors : Anne Mangeney <a href="http://www.ipgp.fr/~mangeney/" target="_blank">http://www.ipgp.fr/~mangeney/</a>, Olivier Castelnau <a href="https://pimm.artsetmetiers.fr/user/54" target="_blank">https://pimm.artsetmetiers.fr/user/54</a>, Vladislav Yastrebov <a href="http://www.yastrebov.fr/" target="_blank">http://www.yastrebov.fr/</a>.

### Research internship
Numerical stability analysis of a flexible beam in a confined fluid
March - August 2017 | Master year 2 <br />
Meudon, France, Onera Aerospace lab, Aerodynamics, Aeroelasticity, Acoustics Department 
- Fluid-Structure interaction modelling, simulations with FreeFem++ run on a cluster
- Stability analysis of a flexible beam in a confined fluid. Possible application to oscillations of pipes or plants in water

### Engineering internship
Analysis of marine vessels stability <br />
April - August 2016 | Gap year <br />
Leiden, Netherlands, Herema Marine Contractor, Marine Engineering Department
- Static and dynamic stability analysis of vessels for heavy lifts installations in matlab and company software
- Anchor positions, ballasting calculations, analysis of the vessels stability under various sea states conditions,
writing of internal and external reports

### Research internship
Sensitivity analysis on a database of catenary geometry and current quality <br />
October 2015 - March 2016 | Gap year <br />
Paris, France, SNCF Railway company, Direction Innovation Research, Mechanical Systems and Interaction
- Processing a database of raw field data and statistical analysis of the geometry and physical parameters of the
pantograph-catenary system calculation of Sobol indices in MATLAB
- Improvement of the maintenance standards ofrailway electric power supply

### Research internship
Experimental study of thermo-acoustic instabilities <br />
May - July 2015 | Master year 1 <br />
Bombay, India, Aerospace Engineering Department, India Institute of Technology Bombay
- Experimental study of thermo-acoustic instabilities in a Rijke tube for improvement of combustion performances
- Processing the laboratory data: Influence of gas burner position, air-fuel mix and flow rate, on induced perturbations

## PUBLICATIONS
- P. Bonnet, L. Pastori, M. Schwabe, M. Giorgetta, F. Iglesias-Suarez, and V. Eyring, Tuning the ICON-A 2.6. 4 climate model with machine-learning-based emulators and history matching, Geoscientific Model Development, 2025 <a href="https://doi.org/10.1017/aog.2019.7" target="_blank">https://doi.org/10.5194/gmd-18-3681-2025</a>.

- A. Sergeant, A. Mangeney, V. A. Yastrebov, F. Walter, J.-P. Montagner, O. Castelnau, E. Stutzmann, P. Bonnet, V. J.-L. Ralaiarisoa, S. Bevan, A. Luckman, Monitoring Greenland ice-sheet buoyancy-driven calving discharge using glacial earthquakes, Annals of Glaciology, 2019 <a href="https://doi.org/10.1017/aog.2019.7" target="_blank">https://doi.org/10.1017/aog.2019.7</a>.

- P. Bonnet, V.A. Yastrebov, P. Queutey, A. Leroyer, A. Mangeney, O. Castelnau, A. Sergeant, E. Stutzmann, J-P Montagner, Modelling iceberg capsize in the open ocean, GJI, 2020, <a href="https://doi.org/10.1093/gji/ggaa353" target="_blank">https://doi.org/10.1093/gji/ggaa353</a>


## EDUCATION

### Master of Science
Modelling and Simulation in Structural Mechanics and Coupled Systems <br />
September 2016 - March 2017, with Honours <br />
ENS Paris-Saclay, ENSTA Paris, Centrale Supelec, top 5 French Uni
- Model reduction
- Fluid-structure interactions
- Numerical error estimators
- Computational fluid dynamics
- Statistics and Probabilities

### Master of Science
Applied Mathematics, Fluid and Solid mechanics <br />
September 2013 - March 2017 <br />
ENSTA Paris, top 10 French Uni
- Signal processing
- Compressible and incompressible fluid dynamics
- Experimental fluid dynamics
- Numerical methods
- Turbulence

### Bachelor of Science
Intensive Science program, pre-requisite for French Uni <br />
September 2010 - July 2013 <br />
Mathematics and Physics (PCSI-PSI*) in Lycée Condorcet, Paris

### High School Diploma
Major in mathematics and life and earth sciences <br />
Sep. 2007 - June 2010 <br />
with Honours <br />
Lycée Louis le Grand, Paris, Prestigious high school with competitive admission <br />

## DOCTORAL TRAINING

### Lectures
-Earthquakes dynamics, IPG Paris 2017
-Pedagogical training, IPG Paris 2017
-Ocean, Atmosphere, Climate ENS Paris 2018
-Contact mechanics, Mines Paris 2018
-Time-dependant seismology, TIDES-cost Prague 2018
-Sun, Northern Lights, UNIS Svalbard 2019

### Glaciology Field Course
UNIS, Svalbard, Norway <br />
5 weeks in February - March 2019 <br />
Doctoral course AG-825 in UNIS, Longyearbyen <br />
Lectures: Glaciology, Thermalregimes, Remote sensing, QGIS Tutorial <br />
8 days of field work: GPR, Ice Coring

### Living-Faults Field Course
Greece <br />
8 days in May 2018 <br />
Doctoral field course, IPGP <br />
Analysis of the Corinth region tectonic activity, lithospheric deformation, and seismic history

### Oceanographic Campaign
Mediterranean Sea <br />
10 days in September 2017 <br />
MOOSE-GE campaign on IFREMER Atalante ship, LOCEAN <br />
Monitoring the impact of climate change on hydrology and biogeochemical cycles in the northwestern Mediterranean Sea

## CONFERENCES AND CONGRESS

 On our work on modelling of iceberg capsize and the source of glacial earthquakes :
- Talk: EGU General Assembly 2021, online
- Seminar: Seismology team, IPGP January 2020 Paris, France
- Seminar: Mechanical simulation team, Mines ParisTech November 2020 Online, France
- Poster: AGU Fall Meeting 2019, Washington, USA, poster presented by Olivier Castelnau
- Talk: CFM French Mechanics Congress, 2019, Brest, France 
- Poster: CDD PhD student conference, doctoral school STEP’UP, 2019, Paris
- Talk: EGU General Assembly 2019, Vienna, Austria, talk presented by A. Mangeney
- Talk: AGU Fall Meeting 2018, Washington, USA 
- Talk: TIDES Advance training school in environmental seismology, 2018, Prague, Czech Republic, 
- Talk: POLAR 2018, Davos, Switzerland, SCAR/IASC Open Science Conference  
- Poster: CDD PhD student conference, doctoral school STEP’UP, 2018, Paris :  Price for the best poster

On our work on automatic tuning of parameters in Climate models:
- Talk: USMILE Meeting, Valencia, October 2023
- Talk: AGU, online, December 2023
- Talk: USMILE Seminar, online, December 2024
- Poster: Atmospheric Physics School, Bad Honnef, juillet 2022
- Poster: EGU, Vienne, avril 2023
- Talk: ICCARUS, online, March 2025
- Talk: AI4PEX EU reviewers meeting, online, October 2025

## AWARDS & GRANTS
- 2018 Best poster award - PhD Student Conference, IPGP, March 2018
- 2017-2020 Doctoral Grant from DGA and STEP’UP Doctoral school
- 2010 National Mathematical Competition, rank 59/2711

## SCIENTIFIC TOOLS
- Programming languages : Python (jupyter-notebook), MATLAB, C++, Fortran 90
- Operating systems : Linux shell, Microsoft Windows
- Documents and presentations editor : LATEX , Microsoft Office
- Other : git, QGIS, Inkscape

## TEACHING
### Graduate-students Mechanics tutorial
Material Resistance and Fatigue Failure <br />
January 2018 - March 2019 <br />
80 hours of teaching in ENSAM Engineering school, Paris

### Undergraduate Students oral examinations
Theoretical and applied physics <br />
September 2014 - June 2015 <br />
44 hours of teaching in intensive science program in Condorcet School, Paris

### High school students private lessons
Mathematics and Physics <br />
October 2013 - June 2014 <br />
40 hours of tutoring to high school students in the region of Paris

## SCIENTIFIC EVENTS AND OUTREACH
- Climate Change Communication : facilitator of 25 Climate Fresk 3-hours workshops (2020-2022), and 2 Climate Fresk facilitation Trainings (2025-2026)
- Scientific instructor : for the Girls on Ice expedition on the Findelen glacier, Switzerland (one week in 2021)
- PhD and Postdocs delegate for the Seismology team of IPGP : co-organisation of seminars in Paris and in Normandy (2018-2020)
- Moderator of a Doctoral School Seminar on Ecology in Academia : with Prof. Masson-Delmotte, Prof. Capet and Dr. Sevestre, online (2020)
- Outreach in Earth and Space Seismology : at the Fête de la Science, IPGP and for the Landing of the Insight mission, Cité des Sciences, Paris (2018)
- Outreach in Glaciology : webinar for APECS-France online (2020), article for children on Glaciology, in Les Romans, Je lis déjà, (Jan 2021)
- Earth and Climate Sciences Poetry : Festival des Idées, Outreach event for Academia, IPGP, (2017 and 2019)
- Seminars on Communication on Climate Change: DLR PhD Symposium (1h, 100 participants), ENSTA Alumni network (40min with Yona Silvy, IPCC, 50 participants), RESCUE projet workshop (15min 50 participantes), (2025, 2026) 
- Organisation of a 24h webinar for the Fresh Eyes on CMIP network. Facilitation of a Science-for-Policy role playing game, moderation of a round table on careers inside and outside academia, and how to engage as a scientist. 

## LANGUAGES 
- French : native speaker, C2
- English : proficient, 5 years in London as a child, C1
- German : advanced, 4.5 years in Munich, B2 (Goethe Zertifikat, 2026)
- Spanish : intermediate, B1
- Japanese : basics

##  VOLUNTEERING AND HOBBIES
- Red Cross volunteer : marauding in a Parisian district, organising a choir to raise funds for the local unit (2018-2020)
- Scouts volunteer, group leader, trainer of new facilitators : pedagogical games, visits of a permaculture farm (2021-2023)
- Arts and sports : 18 years of ballet and contemporary dance, canoe instructor in Hakuba Lyon Adventure Japan (2014), piano, choir, ukulélé, hiking, running, road bike, tennis
