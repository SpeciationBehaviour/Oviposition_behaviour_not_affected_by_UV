# Oviposition_behaviour_not_affected_by_UV
Data and analysis scripts for Borrero (2023) "Oviposition behaviour is not affected by ultraviolet light in a butterfly with sexually-dimorphic expression of a UV-sensitive opsin

<!---
This README uses Markdown syntax, though it is saved in .txt format.
To view the file with its intended text formatting, save a copy as a .md file.
Then you can open it with the browser or text viewer of your choice.
For details on Markdown syntax, see <https://daringfireball.net/projects/markdown/>.
--->

Reference Information
=====================

Provenance for this README
--------------------------

* File name: README_UV-oviposition.Rmd
* Authors: José Borrero
* Other contributors: Daniel Shane Wright, Richard M. Merrill
* Date created: 2023-04-15
* Date modified: 2023-06-15

Dataset Version and Release History
-----------------------------------

* Current Version:
  * Number: 1.0.0
  * Date: 2023-06-15
  * Persistent identifier: DOI: https://doi.org/10.5061/dryad.7m0cfxq0h
  * Summary of changes: n/a

* Embargo Provenance: n/a
  * Scope of embargo: n/a
  * Embargo period: n/a

Dataset Attribution and Usage
-----------------------------

* Dataset Title: Data for the article "Oviposition behaviour is not affected by ultraviolet light in a butterfly with sexually-dimorphic expression of a UV-sensitive opsin"

* Persistent Identifier: https://doi.org/10.5061/dryad.7m0cfxq0h

* Dataset Contributors:

  * Creators: Jose A. Borrero, Daniel Shane Wright, Caroline Nicole Bacquet and Richard M. Merrill.


* Date of Issue: 2023-06-15

* Publisher: Wiley

* License: Use of these data is covered by the following license:
  * Title: CC0 1.0 Universal (CC0 1.0)
  * Specification: https://creativecommons.org/publicdomain/zero/1.0/; the authors respectfully request to be contacted by researchers interested in the re-use of these data so that the possibility of collaboration can be discussed. 

* Suggested Citations:

  * Dataset citation:
    > Borrero, José; Wright, Daniel Shane; Bacquet, Caroline Nicole; Merrill, Richard M. (2023), Oviposition behaviour is not affected by ultraviolet light in a butterfly with sexually-dimorphic expression of a UV-sensitive opsin, Dryad, Dataset, https://doi.org/10.5061/dryad.7m0cfxq0h

  * Corresponding publication:
    > Borrero M., José Antonio; Wright, Daniel Shane; Bacquet, Caroline Nicole; Merrill, Richard M. (2023), Oviposition behaviour is not affected by ultraviolet light in a butterfly with sexually-dimorphic expression of a UV-sensitive opsin. Ecology & Evolution, Wiley. Accepted

Contact Information
-------------------

  * Name: Jose Borrero
  * Affiliations: Department of Evolutionary Biology, Ludwig Maximilian University of Munich
  * ORCID ID: https://orcid.org/0000-0003-0164-496X
  * Email: jborreromalo@gmail.com
  * Alternate Email: jose.borrero@lmu.de
  * Address: e-mail preferred

* Alternative Contact: PI
  * Name: Richard M. Merrill
  * Affiliations: Department of Evolutionary Biology, Ludwig Maximilian University of Munich
  * ORCID ID: https://orcid.org/0000-0002-7872-336X
  * Email: criehl@princeton.edu
  * Address: 405 Guyot Hall, Princeton University, Princeton, NJ 08544

* Contributor ORCID IDs:
  * José Borrero https://orcid.org/0000-0003-0164-496X
  * Daniel Shane Wright https://orcid.org/0000-0002-4066-6718
  * Caroline Nicole Bacquet https://orcid.org/0000-0002-1954-1806
  * Richard M. Merrill https://orcid.org/0000-0003-4527-9298


- - -

Additional Dataset Metadata
===========================

Acknowledgements
----------------

* Funding sources: This research was funded by a European Research Council (ERC) Starter Grant (851040) to R.M.M.


Dates and Locations
-------------------

* Dates of data collection: Field data collected between October 2021 and February 2022

* Geographic locations of data collection: Wild Heliconius erato cyrbia were caught in forests near Balsas (3°51'26.0"S 79°34'05.3"W) and H. himera near Vilcabamba (4°15'57.3"S 79°13'41.4"W), in Southern Ecuador. Wild individuals were used to establish stocks at the Universidad Regional Amazónica Ikiam, Ecuador

- - -

Methodological Information
==========================

* Methods of data collection/generation: see manuscript for details

- - -

Data and File Overview
======================

Summary Metrics
---------------

* File count: 7
* Total file size: 3.2 MB
* Range of individual file sizes: 1010 B - 2.8 MB
* File formats: .csv

Table of Contents
-----------------

* 1_UV_ovipostiton_manuscript.Rmd
* Light_measure_long.csv.zip
* Oviposition_day.csv
* README.md
* UV_oviposition.csv
* egg_count_erato.csv
* red_filter_curve_2.csv

Setup
-----

* Unpacking instructions: Before, using please unzip Light_measure_long.csv.zip

* Recommended software/tools: RStudio version 2023.03.1+446; R version 4.3.0 (2023-04-21)

- - -

File/Folder Details
===================

Details for: red_filter_curve_2.csv.
---------------------------------------

* Description: a comma-delimited file containing data to model the red-filtering LWRh including the red 'receptor', which results from red filtering pigments shifting the sensitivity of LWRh pigment toward longer wavelengths (Zaccardi et al 2006, McCulloch et al. 2021). 

* Format(s): .csv

* Size(s): 1010 B

* Dimensions: 40 rows x 2 columns

* Variables:
  * wavelength: Wavelength values raging from 300 nm to 700 nm
  * red_filter: Photoreceptor sensitivity (ranging from 0 to 1) from the red 'receptor', which results from red filtering pigments shifting the sensitivity of LWRh pigment toward longer wavelengths (Zaccardi et al 2006, McCulloch et al. 2021). 

* Missing data codes: no missing data



Details for: Oviposition_day.csv
---------------------------------------

* Description: a comma-delimited file contains summarized daily oviposition data from Heliconius erato cyrbia and Heliconius himera from the behavioural experiment. 

* Format(s): .csv

* Size(s): 20.3 KB

* Dimensions: 297 rows x 15 columns

* Variables:
  * Date: Date with format dd.mm.yy
  * Day: Experiment day from 1-6 (for a subset of individuals from 1 to 15)
  * Cohort: Pairs of groups that were tested during the same time-period. Ranges from 1 to   7
  * Group: Groups of butterfles that were tested simultaneously. Rages from A-K
  * Cage: Experimental cage where behavioural tests where conducted contains two values 4 and 6
  * Enviroment: Complex or simple enviroment. Refers to the number of plants in the cages.
  * Weather: weather categories, overcast, over50 and under50. For a detailed description see manuscript.
  * Treatment: Filter on the cages UV or Clear. For a detailed description see manuscript
  * Species: Species of Heliconius butterfly, either H. erato cyrbia (cyrbia) or H. himera (himera)
  * Individual ID: C is for cyrbia individuals and H is for himera individuals
  * sum_attempt: Cumulative summ of oviposition attempts within a day
  * sum_egg: Cumulative summ of eggs laid within a day
  * Egg_attempt: Ratio of eggs laid by number of oviposition attempts
  * T: succesfull oviposition attempts within a day (which lead to an egg being laid)
  * F: failed oviposition attempts within a day (which dont lead to an egg being laid)
  
* Missing data codes: "NA" or blank cells.


Details for: egg_count_erato.csv
---------------------------------------

* Description: a comma-delimited file containing the number of eggs laid by H. erato demophoon within a 2h period in STRI Panama (Hausmann et al. 2023) and number of eggs laid by H. erato cyrbia and H. himera for this behavioural experiment

* Format(s): .csv

* Size(s): 23 KB

* Dimensions: 416 rows x 9 columns

* Variables:
  * Date: Date with format dd.mm.yy
  * Group: Groups of butterfles that were tested simultaneously. Rages from A-K
  * Enviroment: Complex or simple enviroment. Refers to the number of plants in the cages.
  * Weather: weather categories, overcast, over50 and under50. For a detailed description see manuscript.
  * Treatment: Filter on the cages UV or Clear. For a detailed description see manuscript
  * Location: Species of Heliconius butterfly, either H. erato cyrbia (cyrbia) or H. himera (himera)
  * sum_egg: Cumulative summ of eggs laid within a day

* Missing data codes: "NA" or blank cells. (The high ammount of NAs is beacuse we extracted information from Hausmann et al. 2023 and some values such as Encrironment, or Weather were nor recored in these experiments)

Details for: UV_oviposition.csv
---------------------------------------

* Description: a comma-delimited file contains summarized daily oviposition data from Heliconius erato cyrbia and Heliconius himera from the behavioural experiment. 

* Format(s): .csv

* Size(s): 63.8 KB

* Dimensions: 777 rows x 19 columns

* Variables:
  * Date: Date with format dd.mm.yy
  * Day: Experiment day from 1-6 (for a subset of individuals from 1 to 15)
  * Cohort: Pairs of groups that were tested during the same time-period. Ranges from 1 to   7
  * Group: Groups of butterfles that were tested simultaneously. Rages from A-K
  * Cage: Experimental cage where behavioural tests where conducted contains two values 4 and 6
  * Enviroment: Complex or simple enviroment. Refers to the number of plants in the cages.
  * Weather: weather categories, overcast, over50 and under50. For a detailed description see manuscript.
  * Treatment: Filter on the cages UV or Clear. For a detailed description see manuscript.
  * Time: Time when the oviposition attempt or egg was laid. Format HH:MM
  * Species: Species of Heliconius butterfly, either H. erato cyrbia (cyrbia) or H. himera (himera)
  * Individual ID: C is for cyrbia individuals and H is for himera individuals
  * First_attempt:
  * First_attempt_minutes: Minutes passed until the frist attempt made after starting the experiment. 
  * First_egg:
  * First_egg_minutes: Minutes passed until the frist egg was laid after starting the experiment. 
  * Attempt: number of oviposition attempts from 1-23
  * Egg: number of eggs laid. 
  * Plant_position: Position of the hostplant, where eggs were laid. Bottom 1/3, middle 2/3, Top 3/3
  * Plant_part: Part of the hostplant, where eggs were laid. For a detailed description see manuscript.

  
* Missing data codes: "NA" or blank cells.


Details for: Light_measure_long.csv.zip
---------------------------------------

* Description: a comma-delimited file containing light irradiance data from the light environment in our experimental cages. 

* Format(s): .csv

* Size(s): 2.8 MB

* Dimensions: 10 rows x 216540 columns

* Variables:
  * wl: Wavelength values raging from 300 nm to 700 nm 
  * direction: Direction where light measurement was taken. For a detailed description see manuscript.
  * measurement_nr: Number of irradiance meassurement (1-6 measurements per part)
  * date: Date when irradiacne measurements wehere taken with format dd.mm.yy
  * time: time when irradiacne measurements wehere taken with format HH:MM
  * weather: weather categories, overcast, over50 and under50. For a detailed description see manuscript.
  * cage: Experimental cage where behavioural tests where conducted contains two values 4 and 6. 
  * filter: Filter on the cages UV or Clear. For a detailed description see manuscript.
  * irradiance: Light irradiance. 



Details for: 1_UV_ovipostiton_manuscript.Rmd
---------------------------------------

* Description:  contains an R-script (notated in Rmarkdown) to reproduce the figures from the manuscript and run the statistical analysis. In order to produce the figures and run the analysis, you will need to download and read-out the csv files above

* Format(s): .Rmd

* Size(s): 79.8 KB
  
- - -
END OF README

