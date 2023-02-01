# anti-Black_lynching_markers.csv

This dataset was created by Dan Royles using data from the [Historical Marker Database](https://www.hmdb.org/)(HMDB).

First, the results of a search for all markers containing the string "lynch" were exported from HMDB on November 30, 2022. Then markers outside of the United States were removed. The resulting data were hand-cleaned to remove those markers that are not pertinent to the history of anti-Black lynching, and annotated to indicate how the marker talks about anti-Black lynching. A field for notes for each marker is also included.

Aside from the columns "Type of Mention" and "Notes," all data were exported from HMDB.

Relevance of markers to the history of anti-Black lynching was determined by reviewing marker text and, in some cases, cross-referencing marker text with other sources, such as [United States National Lynching Data](https://doi.org/10.6077/fwrd-k930). Markers that describe the lynchings of non-Black victims were not retained in the dataset, but markers that memorialize the lynchings of Black victims without mentioning their race *were* retained in the dataset.

## HMDB fields
### MarkerID
a unique indentifier assigned to each marker by HMDB

### Marker No.
marker number assigned by another entity (such as a state historical commission) and sometimes included in marker text

### Title
title of the marker, as given in marker text

### Subtitle
subtitle of the marker, if included in marker text

### Add'l Subtitle
additional subtitle of the marker, if included in marker text

### Year Erected
year that marker was put in place, if known

### Erected By
person(s) or entity/ies responsible for placing marker, if known

### Latitude and Longitude
coordinates for marker location

### Street Address
street address for location of marker, where applicable

### City or Town
municipality in which marker is located

### County or Parish
administrative division of state in which marker is located

### State
state in which marker is located

### Location
discursive description of marker location

### Missing
indicates if marker has been **confirmed** or **reported** missing

### Link
URL for marker on HMDB website

## Annotated fields
### Type of Mention
used to categorize context in which markers refer to lynching, using the following controlled vocabulary:
- **single event--single victim**: marker describes a single lynching event with a single victim, including attempted lynchings in which the intended victim was not killed
- **single event--multiple victims**: marker describes a single lynching event with multiple victims, including attempted lynchings in which one or more intended victims was not killed
- **multiple events**: marker describes multiple discrete lynching events, or a lynching event along with other acts of anti-Black violence, such as race riots
- **lynching as racial terror**: refers to or describes lynching being used to intimidate or punish people of African descent in the United States who claimed or exercised political, economic, or social power
- **anti-lynching activism/legislation/prosecution**: refers to or describes attempts to curtail lynching through political or legal activity
- **lynching--general**: refers to or describes anti-Black lynching as a practice not captured in the above categories

### Notes
descriptive or additional notes about the marker and/or the event(s) it describes
