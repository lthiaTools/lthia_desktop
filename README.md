desktop
=======

desktop tools to run L-THIA 
Repository includes several projects. LthiaCSharp is a C# version of a stand alone desktop spreadsheet calculator which consumes precipitation from https://engineering.purdue.edu. LthiaVB is a visual basic version of an Lthia plug-in for ArcGIS 10.0 - 10.1; requires ESRI VB license as well as spatial analyst license. User provides precipitation.
LthiaTabular is ArcGIS toolbox 10.1 - 10.2.2 (python) version with tabular output, requires spatial Analyst extension. Precipitation is CLIGEN synthetic rainfall, user specifies 5 - 50 years and automatically downloads from lthia.agriculture.purdue.edu. No arrangement for user precipitation.
RasterRunoff is ArcGIS 10.1 - 10.2.2 Toolbox for Lthia with raster-based analysis and runoff output as raster. Very heavy computation time. Includes tools for Curve Number map and for precipitation station layer construction. Precipitation may be observed data ( 30 years) from https://engineering.purdue.edu or CLIGEN synthetic rainfall, user specifies 5 - 50 years and automatically downloads from lthia.agriculture.purdue.edu.  Requires Spatial Analyst.
