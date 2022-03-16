---
## Topic: 
I want to design a map that explores historic parcel ownership/purchases of the University of Kentucky on the Lexington main campus. 
## Question: 
I want to identify when the University of Kentucky purchased specific parcels on main campus, from who (person, organization, etc.), and the original size. 
## Significance: 
I want to design an interactive map that will allow users to easily search and view University of Kentucky owned parcels. There is not a single location for this data. Finding additional information requires digging through deed books and various documents. More recent parcel data can be obtained from the LFUCG PVA; but older sections of campus have been merged into large parcels, instead of the original parcel size they were purchased at. Some historic data is currently in a CAD DWG, which would need to be geospatially referenced and digitized. Another pressing need is that the CAD document is maintained by a single person. With many folks retiring, it is important that a resource is available before the 'keeper' of this data retires.

## Nascent project topic ideas and datasets discussion
**UKY Parcel Ownership Transfer** - In my current position with ITS Information Services, I work closely with UK Facilities Management and their datasets. Our department has identified a need for historic parcel/plat data to be digitized and made available in an easy to use map environment. This is something our department has wanted to complete for a while, but have not been able to get funding to support the development. More recent parcel data can be obtained from the LFUCG PVA; but older sections of campus have been merged into large parcels, instead of the original parcel size they were purchased at. Historic data is currently in a CAD DWG, which would need to be digitized. This document is maintained by a single person. With many folks retiring, it is important that a resource is available before the 'keeper' of this data retires.

## Other Possible Projects
- **UKY Bike Count Analysis** - Our department coordinates with Transportation Services to complete an annual bike count of campus (2016-2020). This involves a group of volunteers going across campus and counting bikes at racks over the course of an hour. Field Maps is used to collect the data, so data is already available in GIS format. Would develop an interactive map to analyze the compacity data from 2016-2020. Identify areas that are over or under utilized to better allocate resources. 
  - Rack Locations - https://maps.uky.edu/bicycle/
  - Annual Data - ITS Information Services 
- **Teen Pregnancy Rates** - Examine teen pregnancy rates in US  from the last 5 years and identify any trends. Possibly show comparisons with race, economic status of community, access to publicly-funded family planning services. 
  - https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm
  - https://www.cdc.gov/nchs/data-visualization/teen-births/index.htm
  - https://www.americashealthrankings.org/explore/health-of-women-and-children

## Scott Hogue Comments
Historic Deed Data - UKY Campus Physical Plant - Engineer Facilities & UKY ITS Information Services - Facilities Library
- Scott Hogue (2018) - As we discussed, this was drawn on an existing geo-referenced base map of the city streets, but it is not a survey. It was drawn from existing deed and plat information. Distances shown on the lots and R/W’s were taken from the deeds and/or existing subdivision plats. It only shows parcels as described when they were conveyed to UK and does not show subsequent sales for road widening, easements, etc. Some parcels were sold to Greek and other organizations, and then purchased back by UK and leased back, etc. It is not an all-inclusive map. There are a few holes and several acquisitions that have been made since it was drawn are not on the map. That would be a good project to update the map. 

Attribute List
  | Field Name | Description | Type | Comment |
  | :--- | :--- | :--- | :--- |
  |CampusCode|Two digit code for UK campus location|Text - 2||
  |FIS_Number||Text - 20||
  |PVA_Number||Text - 20||
  |Owner|Owned by UK or no|Text - 20|UK/Non-UK/TBD|
  |LocationDisplay||Text - 30|Inside Boundary/Outside Boundary/TBD|
  |Address||Text - 50||
  |Zip||Text - 10||
  |County||Text - 30||
  |PVA_Acre||Numeric||
  |FileCab||Text - 5||
  |Drw||Text - 5||
  |DB|Deed Book Number|Text - 10||
  |DB_Page|Deed Book Page|Text - 10||
  |Deed_Date||Date||
  |GRANTOR||Text - 50||
  |GRANTEE||Text - 50||
  |Deed_Address||Text - 50||
  |Alternate_Name||Text - 50||
  |Deed_Notes||Text - 255||
  |Other_Docs||Text - 255||
  |Source||Text - 255||
  |Label||Text - 255||
  |Link||Text - 255||
  |Comment||Text - 255||