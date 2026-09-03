# AirBnB London Listings Analysis

### AirBnB revenue Model
AirBnB's business revenue model works on a flat ~15.5% commission fee on the booking price which the host pays. Therefore the key drivers in AirBnB's revenue model are Nights Booked and Property Price. Increases in both of these factors result in greater revenues.

### Analysis Overview
Therefore the analysis on the Property Listings below focusses on the Property Price, highlights characteristics explaing variability in Price and identifies outliers within subgroups of properties which could be used by AirBnB to notify hosts that their property is mis-priced vs similar listings.

### Findings Summary
Price was found to be driven by the number of guests that can be accomodated (size), location and property type. Therefore outliers were detected within location and guests accommodated groups using the percentile ranks (bottom 10% as low pricing, top 90% as high priced).

### Limitations
Due to this dataset only including listings data and not booking or search & Conversion data, the outliers can only highlight potential mis-pricing. To understand if the property is actually mispriced, performance metrics would need to be included and this should be a pre-cursor to future analytics of the whole pictur. There is also the potential for this analysis to be the foundations of a full pricing elasticity solution.
