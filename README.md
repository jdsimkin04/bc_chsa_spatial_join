# Spatial Join of BC CHSA Data to Point Data

Welcome!

In this repo, I have an rmarkdown that demonstrates a quick way link the British Columbia (BC) Community Health Service Area (CHSA) shapefile, with any given point data (E.g. imagine you have health events by longitude / latidude). We'll do this through a spatial join!

## What is the BC CHSA shapefile?

The CHSA is the smallest health administrative area in BC. It was created to facilitate community level health analyses. The shapefile is openly available through the [BC Gov data catalogue](https://catalogue.data.gov.bc.ca/dataset/community-health-service-areas-chsa). It also contains attribute data - contextual information related to that CHSA. These include but are not limited too:

-   Corresponding health administrative areas (LHA, HSDA, HA)
-   Census population
-   Area km2
-   Level of urbanization

## Why would we want to link the CHSA to data?

-   To assign rural-urban status in BC to point data (e.g. health events)
-   To assign CHSA, LHA, HSDA, or HA in BC

## Want to see this in an HTML preview?

Check out my Rpubs: [https://rpubs.com/jdsimkin04](https://rpubs.com/jdsimkin04/907820)

## Feedback

If you find yourself using this, I'd love to hear from you. Happy to post any of your info products (publcation, reports) that used this code.
