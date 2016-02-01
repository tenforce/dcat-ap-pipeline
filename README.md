# dcat-ap-pipeline

This repository contains a simple way to create DCAT-AP records based on Excel templates.  

Datasets are described using DCAT-AP. For the specification see https://joinup.ec.europa.eu/catalogue/distribution/dcat-ap-version-11. The specification is also downloadable directly.

A template has to be completed for each dataset. This template refers to some default entities such as the publisher and contactpoint. These have been collected in this file.template has to be completed for each dataset. This template refers to some default entities such as the publisher and contactpoint. These have been collected in this file.

Each instance is being treated by a UnifiedViews pipeline. The pipeline converts the meta data into RDF.

Usage & installation steps
--------------------------
1. deploy UnifiedViews: for instance deploy the toolbox via the vagrant setup as specified
2. upload the pipeline
3. create the directories: 
   ` mkdir -p $HOME/Documents/inputs `
   ` mkdir -p $HOME/Documents/results `
   ` chmod 777 $HOME/Documents/results `
4. copy the input pipe to the inputs directory
5. run the pipeline and find output in the results directory

