# _LITsis_

## _LITsis_ - what is it?

**_LITsis_** short for **LIT**erature anal**sis** is a simple Python based tool for analyzing meta and functional trends for a set of **reserach articles** from [e.g., web of science](https://mjl.clarivate.com/home). Additionally, further a set of tools (sensitivity, visualization) to analyze the mathmatical formulations in those articles.

Codes developed were by part of the academic course work at [TU Dresden](https://tu-dresden.de/bu/umwelt/hydro/igw) and [HTW Dresden](https://www.htw-dresden.de/hochschule/fakultaeten/bauingenieurwesen/studium/lehrgebiete/wasserwesen). Basically, the codes allows to perform **meta analysis** and **functional analysis** of the literature (such as journal articles). 

## Steps for using code 

1. Make sure that you have Python installed in your system and the Python libraries provided in the [requirements.txt](https://github.com/HTWDMAR/Litansis/blob/main/requirements.txt)
2. Download the code as a zip file and extract it to any folder.
3. From the folder, run the code using [VScode](https://code.visualstudio.com/) or any such IDE that can run Python.
4. To conduct **Meta Analysis** you need to make sure the _csv_ file (of literature obtained from e.g., web of science) in which the data about all the research articles is in the simillar format as mentioned in the   code and name of all.
5. **Sensitivity Analysis** of each Parameter in a given equation can be checked, codes such as Local Sensitivity and FAST Sensitivity can be used. In either of them the Equation and the range around which the variables required to calibrate has to be given in as Input. 
6. To carry out the **Functional Analysis**, codes provided requires the _function_ (to be analyzed) as input at the start and the code runs a varitey of  Monte Carlo simulations based on the initial conditions and based on the simulations a common regression line is produced with the main goal to genralize the equation. 

## Few code output (e.g., clogging of riverbed)

<img src="https://user-images.githubusercontent.com/86523952/207420463-0e320f97-4cab-4a95-975f-7afb711637fa.png" width="500" height="300">

Word Cloud of Produced from meta data analysis of various abstracts 

![image](https://user-images.githubusercontent.com/86523952/207420668-0d3d5a76-a149-4496-9551-65ce389bf5de.png)

Results from FAST Sensitivity Analysis 

![image](https://user-images.githubusercontent.com/86523952/207420810-a3777257-5a7e-4de2-8c29-e5f64a760304.png)

Results from Local Sensitivity Analysis

## License and Authors

The codes in this site are CC BY 4.0 licensed. The license wording can be found [here](https://creativecommons.org/licenses/by/4.0/).
Basically, for using code from here- the original authors should be credited.

Following authors are credited for this version [![DOI](https://zenodo.org/badge/576731272.svg)](https://zenodo.org/badge/latestdoi/576731272)
of the code (names not in any order):

1. **Vibhu Batheja** - Main code developer
2. **Dr Prabhas K Yadav** - Main conceptualization and basic code development
3. **Priyadarsini Manikandan** -Project Team member
4.  **Abdul Munim Tahir** - Project Team member  
5. **Prof. Dr. T. Grischek** - Supervisory support on contents
6. **Prof. Dr Andreas Hartmann** - Supervisory support on contents

## References

coming up
