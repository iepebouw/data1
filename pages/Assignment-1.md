---
layout: page
title: Assignment 1
permalink: /assignment-1
nav_order: 2
---

# Amsterdam Paralympics
Paris is hosting the Paralympics in 2024. One of the events at the Paralympics is an open water
swimming event in the Seine (apparently the water is clean or so the French say). Since the City
of Amsterdam thinks it is beter than Paris, they want to host an event before the Paralympics,
snubbing the Parisians. The idea is to host a 5km. open water swimming event through the
canals of Amsterdam. We were asked by the municipality of Amsterdam to advise on the
feasibility of the event from the perspective of the safety of the partaking athletes from an
environmental perspective. The event is going to be hosted in May.

There are several requirements and wishes to take into account. First of all, the event should not impede the waterway of commercial boats. Moreover, the event preferably also does not have an impact on the routes of canal boats. On top of this, the water should be safe to swim in. During other events, like the [Amsterdam City Swim in 2015](https://magazines.rivm.nl/2018/03/infectieziekten-bulletin/zwemmen-de-gracht-hoe-groot-zijn-de-infectierisico%E2%80%99s#:~:text=In%20de%20watermonsters%20van%20alle,maal%20verhoogde%20normaalwaarde%20van%20E.), a considerable amount of participants reported sicknessess after a week. Gastrointestinal illness causes diarrhoea, 
indigestion, nausea and stomach-ache. The water in the canals should be regularly checked and monitored, especially during the weeks around the event. To conclude, data about the intensity of the use of the canals is needed, popular routes for commercial and canal boats and the water quality are needed. 

In the table below we listed useful data-sets covering the above mentioned requirements. 

| Name                                   | Data type  | Source | Comments             |
|:-------------------------------------------------|:---------------|:----------------|:-------------------------------|
| Maps Data Amsterdam| CSV | [https://maps.amsterdam.nl/open_geodata/](https://maps.amsterdam.nl/open_geodata/) |Website with maps needed |
| Zwem- en speelwater | CSV | [https://maps.amsterdam.nl/zwemwater/](https://maps.amsterdam.nl/zwemwater/) | Map that shows how canals are not an official swim location |
| Op- en afstapplaatsen en ligplaatsen passagiersvoertuigen | CSV | [https://maps.amsterdam.nl/varen/](https://maps.amsterdam.nl/varen/) | Map that shows that the canalbelt is intensively used by boats|
| Grachtenmonitor 2022 | pdf/URL | [https://openresearch.amsterdam/nl/page/92981/grachtenmonitor-2022](https://openresearch.amsterdam/nl/page/92981/grachtenmonitor-2022) | Document that contains information about how intensely a waterway is used |
| Water in Amsterdam - Meetresultaten kwaliteitsonderzoek oppervlaktewater 2019 | XLSX | [https://api.data.amsterdam.nl/dcatd/datasets/lAqjIsj-_a7psg/purls/4](https://api.data.amsterdam.nl/dcatd/datasets/lAqjIsj-_a7psg/purls/4) | Data sheet with data about water quality |
| (Swim) water quality modelling in the city of Amsterdam | pdf | [https://edepot.wur.nl/528034](https://edepot.wur.nl/528034) | Thesis about water quality in Amsterdam, e.g.information about what influences it |
| Zwemwater | URL | [https://www.zwemwater.nl/schoon_water_kwaliteit](https://www.zwemwater.nl/schoon_water_kwaliteit) | Data about swim water quality, measurements |

From the [figure](https://openresearch.amsterdam/nl/page/92981/grachtenmonitor-2022) below we can conclude that the canalbelt is an intensively used waterway for commercial boats and tour boats, especially during the summer the event would have too much of an impact on the waterway. Thus, the event should take place outside of the city center canals.  


![image](https://github.com/iepebouw/data1/assets/144791642/aaf274e0-351c-40aa-8ca7-338b1d4b4446)



Moreover, from the data-sets in the table can be derived that there is are no official open water swimming locations in Amsterdam. Official swimming locations are monitored regularly (although once a month does not seem enough to us), so it becomes clear which water is safe to swim in ([Zwemwater](https://www.zwemwater.nl/schoon_water_kwaliteit)). Before the event the water should be more frequently monitored and the canals need to be cleared from obstacles in the water, like bikes and other bulky objects. Escherichia Coli (E. Coli) and Enterococci are harmful bacteria that could cause sickness when it is present in large quantities. These bacteria originate mainly from sewage systems. There is a higher risk of the presence of these bacteria after intense rainfall, since this might lead to the overfowing of sewage systems. As can be seen in the [map](https://www.zwemwater.nl/) below, currently there are no measurements done on these bacteria in the center of Amsterdam. In order to choose a suitable location for the Paralympics, sufficient data about harmful bacteria like E. Coli is needed, and measurements should be taken constantly, and with extra care after heavy weather events. 


![image](https://github.com/iepebouw/data1/assets/144791642/0b80ea40-5a17-4aa9-9b05-0350db63be6b)
















Go to the next assignment: [TourBoats]({{site.baseurl}}/assignment-2)
