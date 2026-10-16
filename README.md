# Arretine_Similarity_Indices
Repository for the data and code used in the analysis within the article 'Exploring Patterns of Trade and Consumption of Arretine, Pisan, and Central Italian Terra Sigillata in Northern Italy using Similarity Indices'

## Data
The data stored here forms the basis of the analyses undertaken in the article. The primary source of the data was the Römisch-Germanisches Zentralmuseum (RGZM) database ‘Names on Terra Sigillata’. The original database can be found [here]. (https://www1.rgzm.de/samian/home/frames.htm) The dataset was supplemented by a corpus of sigillata stamps gathered from excavation reports not included in the RGZM database, which enhanced existing assemblages present in the database (such as Cremona and Turin).

The database contains 1419 Arretine, Pisan, and Central Italian terra sigillata stamps from 25 sites across Northern Italy. It is stored here in csv. format. The file name is italianstamps.csv

### Structure

The CSV file contains nine columns containing the following information: 

**id:** Unique identifier for each stamp in the dataset.

**rgzm_id:** A stamp's ID within the RGZM dataset (if applicable).

**pottername:** Reconstructed name of the potter attested by the stamp.

**production:** Specific location of the sherd's production (if known).

**production_area:** Sub-produciton of terra sigillata (e.g. Arretine, Northern Italic, South Gallic etc.)

**date:** Chronology for the activity of the potter (if known).

**die:** Unique die number for the stamp from Oxé, A., Comfort, H. and Kenrick, P.M. 2000. *Corpus vasorum Arretinorum: a catalogue of the signatures, shapes and chronology of Italian sigillata*. Bonn: Habelt.

**site:** Location where the stamp was found.

**bibref:** The publication the stamp is recored in (if not included in the RGZM database).

## Notebooks
The R notebooks used to generate the data analysis figures are stored in this repository.

Each notebook reproduces one figures, numbered in the same way as in the publication.

Each notebook is structured in the same way:

Import packages

Read in data

Data analysis

Plot the graphs
