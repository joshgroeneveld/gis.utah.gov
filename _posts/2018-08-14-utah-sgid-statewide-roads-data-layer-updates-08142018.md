---
title: Utah SGID Statewide Roads Data Layer Updates 08/14/2018
author:
  display_name: Greg Bunce
  email: gbunce@utah.gov
date: 2018-08-14
categories:
  - Featured
tags:
  - roads
---

Updates were recently made to the SGID10.Transportation.Roads feature class that resides on the [Utah SGID ArcSDE database server]({{ "/sgid-database/" | prepend: site.baseurl }}).

Updated roads data is also available as shapefiles and file geodatabase files for download on the [SGID Roads and Highway System download page]({{ "/data/transportation/roads-system/" | prepend: site.baseurl }}).

These updates are also reflected in [AGRC's address locators]({{ "/data/address-geocoders-locators/" | prepend: site.baseurl }}) and the [Utah Next-Generation 911 GIS Database]({{ "/data/911/" | prepend: site.baseurl }}).


The following are highlights from this month's update:

#### County Updates: Beaver

- **Beaver County:** Obtained roads data on 06/14/2018: added new roads, updated road names and address ranges, etc. Previous update was on 07/18/2017.

- **Box Elder County:** Obtained roads data on 06/08/2018: added new roads, updated road names and address ranges, etc. Previous update was on 04/12/2018.

- **Davis County:** Obtained roads data on 07/05/2018: added new roads, updated road names and address ranges, etc. Previous update was on 06/27/2018.

- **Emery County:** Obtained roads data on 07/02/2018: added new roads, updated road names and address ranges, etc. Previous update was on 07/18/2017.
 
- **Salt Lake County:** Obtained roads data on  07/09/2018: added new roads, updated road names and address ranges, etc. Previous update was on 06/27/2018.

- **Utah County:** Obtained roads data on 07/03/2018: added new roads, road names and address ranges, etc. Previous update was on 06/27/2018.

- **Wasatch County:** Data requested on 06/07/2018 and 06/29/2018 but not received.

- **Washington County:** Obtained roads data on 07/09/2018: added new roads, road names and address ranges, etc. Previous update was on 06/27/2018.

- **Weber County:** Data requested on 06/29/2018 and 07/09/2018 but not received.

#### UDOT Route System:

- The `DOT_F_MILE` (From Milepost) and `DOT_T_MILE` (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated.
- The following SGID feature classes were also updated: SGID10.Transportation.UDOTMileposts; SGID10.Transportation.UDOTRoutes_LRS; and SGID10.Transportation.UDOTTenthMileRefPoints.