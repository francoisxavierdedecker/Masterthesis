# Masterthesis

Introduction

The aim of the thesis on multimodal transport is to provide a tool that
could be used by the different stakeholders to analyze the European transport sector and help them adjust their policy. Using aggregated monthly
transport data for the 2018-2022 period provided by Stabel, an application
was built to help visualize, analyze, and interpret the flows of transported
freight through Belgium. Using the R package “Shiny” a web application
generates graphs representing the flows of freight that pass through Belgium based on several properties like the type of freight or the transportation
mode. Using a network analysis, the application will be able to give insights
into the evolution of transport routes (edges) and the evolution in the importance of actors like ports or trading partners (nodes). The application
was built to use the data for Belgian waterways but could be
scaled using European data and data from other transport modes (train,
aviation, pipeline)

How to Install the Project

The R Markdown file "Shiny app markdown Github version.Rmd" was written using R 4.1.1 version. The packages necessary to run the app can be found in the first chunck.
To run the app, five extra files should be downloaded and the path to these files should be changed in the second chunck.

1) Coordinates.csv
2) Coordinatesaggregated.csv
3) WaterwaysNetwork.zip
4) DummyDataFreight.csv
5) DummyDataStatistics.csv

The first two files contain the coordinates for a list of ports, the third file contains a section of the Copernicus waternetwork displaying a subset of river and canal segments.
The last two files are dubby data reflecting a fictive flow of freight. 

How to run the App

The app can be run by running all the chuncks, when the packages are loaded and the paths are attributed.
The app will launch at the end on a local web page.

Note

Given that the app was developed using Statbel's data, with a slight different structure, not all panels in the app might be working for some chosen filters.
An update will be provided to solutionize this issue.
