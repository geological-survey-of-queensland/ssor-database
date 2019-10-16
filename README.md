# Sites, samples, observations &amp; results database <br>(Geological Properties Database)

One of the primary purposes of the Geological Survey of Queensland (GSQ) is to improve understanding of Queensland's resource potential.

GSQ creates, collects and provides geoscience data, information and advice on Queensland’s mineral resources, coal, coal seam gas, petroleum, including unconventional petroleum, oil shale and geothermal energy. GSQ creates this knowledge through a range of geoscience projects and initiatives including industry exploration grants.

In summary, GSQ seeks to understand the geological properties of the State of Queensland, both surface and sub-surface.

## Geological properties data model
<p align="center">
<img src="https://github.com/geological-survey-of-queensland/ssor-database/blob/master/images/geological-properties-model.svg" width="560"><br>
Figure 1: Geological properties data model</p>

### A plain English definition
We seek to understand the geological properties of a geological or administrative feature. We undertake a survey
on the feature, either as a whole feature, or on subsets of the feature. The survey yields samples. We conduct observations on the samples using a particular procedure. The observation yields results as measured values. We interpret the results to understand the geological properties of the feature.

### Definitions
#### Geological property
* The observable or measureable properties of a geological or administrative feature.  
* Examples: minerals, hydrocarbons, water properties.  

#### Geological or administrative feature
* Geological features have properties that are of interest for commercial, environmental and societal reasons.  
* Administrative features are spatial features that are defined and managed by regulatory agencies.
* Examples: basin, orogen, province, traugh, craton, permit, sub-block.

#### Site
* A sub-set of the geological or administrative feature.  
* Examples: borehole, stream, seismic line.

#### Survey
* The one-off event of examination of a geological or administrative feature.
* Examples: seismic survey, geochemical survey, gravity survey, magnetotelluric survey.

#### Sample
* The enduring extract from the geological feature.  
* Examples: 

#### Observation
* An act of carrying out an observation using a _procedure_ to estimate or calculate a value of a geological or administrative feature.
* Examples: 

#### Result
* The result of the observation stored as a value together with the unit.  
* Examples: concentrations, quality, reserve size

## The Geological Properties Database
The Geological Survey of Queensland is creating a new Geological Properties database to:  
* Replace the existing Surface Geology functionality in the MERLIN system.  
* Replace the Cores and Cuttings functionality in MERLIN.  
* Replace the Mineral Occurrences functionality in MERLIN.  
* Replace the Aerial Geophysics functionality in GEM.
* Capture the primary Geochemical data recorded in the Explorer3 system.  
* Provide a repository for new data created by the department.  
* Provide a repository for new data submitted to the department.  

### Objectives of the Geological Properties Database
TO DO

## Geological Properties Database conceptual data model
TO DO  

## Geological Properties Database data elements
| Data Concept | MERLIN table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|--|--|
|Site|--|--|
|Survey|--|--|
|Sample|--|--|
|Observation|--|--|
|Result|--|--|  

## Geological Properties Database vocabularies
| Vocabulary | Example values |
|---|---|
|Geoadmin features|--|
|Site types|--|
|Survey types|--|
|Sample types|--|
|Observation types|--|

* Geoadmin features  
* Site types  
* Survey types

## Mapping to MERLIN Surface Geology tables
| Data Concept | MERLIN table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|--|--|
|Site|sgf_sites|--|
|Survey|--|--|
|Sample|sgf_survey|--|
|Observation|sgf_explore_techniques|--|
|Result|--|--|

## Mapping to MERLIN tables
| Data Concept | MERLIN table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|--|--|
|Site|--|--|
|Survey|--|--|
|Sample|--|--|
|Observation|--|--|
|Result|--|--|


## Mapping to GEM Aerial Geophysics Surveys tables
| Data Concept | GEM table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|Aerial geophysics spatial extent|--|
|Site|--|--|
|Survey|--|--|
|Sample|--|--|
|Observation|--|--|
|Result|--|--|

## Mapping to GEM Seismic Surveys tables
| Data Concept | GEM table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|Aerial geophysics spatial extent|--|
|Site|--|--|
|Survey|--|--|
|Sample|--|--|
|Observation|--|--|
|Result|--|--|

## Mapping to Explorer3 tables
| Data Concept | Explorer3 table | Comments |
|---|---|---|
|Geological Property|--|--|
|Geoadmin Feature|--|--|
|Site|--|--|
|Survey|--|--|
|Sample|--|--|
|Observation|--|--|
|Result|--|--|

## See also


## Licence
This code repository's content are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), the deed of which is stored in this repository here: [LICENSE](LICENSE).

## Contacts
*System owner*:  
**Mark Gordon**  
Geological Survey of Quensland  
Department of Natural Resources, Mines and Energy  
Brisbane, QLD, Australia  
<mark.gordon@dnrme.qld.gov.au>  

*Author*:  
**David Crosswell**  
Enterprise Architect  
Cross-Lateral Enterprises   
<https://crosslateral.com.au>  
