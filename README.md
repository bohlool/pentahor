pentahor
========

Execute R Scripts from Pentaho Data Integration

Pentaho R Integration Plugin is used to execute R code direct from Pentaho Data Integration (PDI).
R Script Plugin can be downloaded here: [Downloads](http://dekarlab.de/wp/?p=100)


Installation

R script plugin can be installed by performing the following steps:

1) Copy the plugin folder (RScriptPlugin) into the folder of your PDI installation:
data-integration\plugins\steps

2) Install R project from the site http://www.r-project.org/

3) Install rJava package in R by executing: install.packages(“rJava”)

4) Copy JRI library rJava/jri/jri.dll (windows) or rJava/jri/libjri.so (linux) to: data-integration/libswt/{your operation system}

5) Specify location of R using R_HOME environment variable. For windows, it is also needed to put in PATH variable the path to R.dll, for example: C:\R\R-3.0.2\bin\{your operation system}

6) The plugin can be found under Sripting Folder in Design Tab

For more information visit [Dekar Lab](http://dekarlab.de/wp/?p=5)
