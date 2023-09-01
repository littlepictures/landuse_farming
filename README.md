# Continental farmland comparison, 1992 to 2015

## Background on this CLIP

This infographic shows the comparative change in land used for farming in four countries, across four continents, from 1992 to 2015.  This comparison shows how land used for farming has grown in some countries and reduced in others during the period measured.  Increasing use of land for farming leads to less available habitat for wildlife and a general drop in biodiversity.

Countries studied (left to right): The Netherlands (Europe), Nicaragua (Americas), New Zealand (Oceania) and Nigeria (Africa)

## Data Sources

The CLIP uses the following datasets:
- [Global Land Cover Maps, Version 2.0.7](https://catalogue.ceda.ac.uk/uuid/62c0f97b1eac4e0197a674870afe1ee6)
- Datapoint: country lc class areas (mosaic >50% cropland / <50% natural tree, shrub, herbaceous cover)

## Data Preparation

To prepare the data, follow these steps:
- Download the CSV file for the country(ies) you'd like to study and open in an appropriate editor
- Locate the column for the datapoint you're interested in. In the example provided, this was 'Mosaic: > 50% cropland/< 50 % natural tree, shrub, herbaceous cover', which represents farmland coverage
- Round the values to the nearest full number, for simplicity
- Measure the highest and lowest value for each of the countries under study, to work out the comparative range. In the example provided, the comparative range was 17% (from -5% to +12%) of total lc in the measured datapoint.

## Creating Visualisations

To create this visualization:
- Create a vector shape, representing each country under study and vertically align them across a horizontal plane.
- Create a line in the centre of the shapes, representing the start year of dataset. In the example provided, this was 1992.
- Create an overlay shape for each country, to represent the comparitive rise or fall in % of land coverage for your chosen measurement, since the start of the dataset. 

## CREDITS & LICENSE
- Idea by: [Imperative Space](https://www.imperative.space)
- Processing Scripts by: [Imperative Space](https://www.imperative.space)
- Visualisation by: [Imperative Space](https://www.imperative.space)

The code in this repository is published under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
The content in this repository is published under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
