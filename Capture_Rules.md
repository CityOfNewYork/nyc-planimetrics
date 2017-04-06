### NYC Planimetric Database

#### Purpose
The purpose of this document is twofold. First, it is intended to define the capture rules for each planimetric feature collected as part of the planimetric update project. As such, this document is meant to clarify questions regarding how the features were captured, provide feature descriptions, and illustrate any exceptions that may apply. Second, since this document provides a wealth of information that would benefit users working with the data, we decided to make it accessible as a secondary source of documentation. This document is not intended to replace the metadata included with the planimetric features but rather to function as an additional source of information. Lastly, the documentation originated from previous planimetric updates. The documentation has evolved and has been refined over each successive planimetric update cycle; and will continue to be extended and maintained over the course of future updates.

#### Introduction
One of the core functions of the NYC Department of Information Technology and Telecommunications (DoITT) GIS group is to maintain and distribute an accurate 'basemap' for NYC. Collectively, the basemap includes the digital orthophotography and planimetric features. The basemap provides the foundation upon which virtually all other geospatial data within New York government is registered. Ensuring its completeness and accuracy is fundamental to the Group’s core mission.

#### Background
Planimetric mapping is the capture of geographic features from aerial survey (i.e., capture of aerial photography) that are traditionally mapped in two dimensions and are therefore exclusive of elevation. Quite simply these are the visible features that can be digitized from aerial photography. Often referred to as planimetric features or simply planimetics, these geographic features in their sum total essentially represent the base map data (i.e., layers) for a specific area.
NYC DoITT first developed a planimetric database in 2000. The data was captured from the first ‘modern’ aerial survey of the New York City that took place in 1996. Referred to at that time as the NYC Landbase, components of this effort were the establishment of:

• a ‘database design’ (the delivery was ArcInfo coverages)
• coverage parameters (e.g., scale, projection, precision, fuzzy tolerance and dangle length)
• the specific features to be captured
• and a classification scheme (i.e., feature codes)
The delivery of the data was by 2,500′ x 2,500′ tiles, which directly corresponded to the orthophotography tiles.

#### Updates
A subsequent ad-hoc update to the planimetric database was done in 2004. This update was based on aerial surveys from 2001 (Manhattan and Staten Island) and 2002 (Bronx, Brooklyn and Queens). This update conformed to the previous database design. In 2006, DoITT formalized the update frequency of the planimetric database and aerial surveys. The aerial photography would be captured on a two-year cycle and the planimetrics a four-year cycle. The first regularly-scheduled planimetric update was based on the 2006 aerial photography and delieverd in 2008.

With each subsequent update, refinements have been made. New features and domains have been added, obsolete features have been removed, features have been captured in three dimensions, a seamless database has been produced and the time between aerial capture and delivery of the planimetrics has been shortened. For a complete list of the captures, see below.

#### Current Imagery
The source imagery for the current planimetric update was captured on the following dates:

• Manhattan - June 24, 2014
• The Bronx, Brooklyn, Queens and Staten Island - April 1st through April 25th, 2014
• Final delivery of all imagery – April 10, 2015

Based on the stereo models developed from the raw imagery and aerotriangulation, the planimetric features were updated or new features captured for the entire City. The project began March 2015 and was completed February 2016.

#### Previous Captures
|     |     |     |
| --- | --- | --- |
| <p align="left">**Planimetric Delivery**</p> | <p align="left">**Year of Imagery**</p> | <p align="left">**Download Link**</p> |
| 2000 | 1996 | [download] (https://data.cityofnewyork.us/Transportation/NYC-Planimetrics-Historic-2000-/xd8h-7j2h) |
| 2004 | 2001, 2002 | [download] (https://data.cityofnewyork.us/Transportation/NYC-Planimetrics-Historic-2004-/49mj-4gmb) |
| 2008 | 2006 | [download] (https://data.cityofnewyork.us/Transportation/NYC-Planimetrics-2008/dja4-zgtf) |
| 2012 | 2010 | [download] (https://data.cityofnewyork.us/Transportation/NYC-Planimetrics-2012/3nr6-bnks) |
| 2016 | 2014 | [download] (https://data.cityofnewyork.us/Transportation/NYC-Planimetrics/wt4d-p43d) |

#### Table of Contents
&nbsp;&nbsp;&nbsp;&nbsp;[Imagery and Data Specifications](# imagery-and-data-specifications)
&nbsp;&nbsp;&nbsp;&nbsp;[General Attribute Information](# general-attribute-information)

&nbsp;&nbsp;&nbsp;&nbsp;**FEATURE CLASSES**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Boardwalk**](# boardwalk)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Building Footprint**](# building-footprint)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Cooling Towers**](# cooling-towers)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Curb**](# curb)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Elevation**](# elevation)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Hydro Structure**](# hydro-structure)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Hydrography**](# hydrography)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Median**](# median)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Misc Struct Poly**](# misc-struct-poly)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Open Space**](# open-space)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Park**](# park)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Parking Lot**](# parking-lot)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Pavement Edge**](# pavement-edge)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Plaza**](# plaza)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Railroad**](# railroad)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Railroad Structure**](# railroad-structure)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Retaining Wall**](# retaining-wall)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Roadbed**](# roadbed)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Shoreline**](# shoreline)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Sidewalk**](# sidewalk)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Sidewalk Centerline**](# sidewalk-centerline)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Swimming Pool**](# swimming-pool)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Transport Structure**](# transport-structure)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Under Construction**](# under-construction)


# Imagery and Data Specifications
Digital planimetrics were derived using the imagery products delivered with the 2014 New York Statewide Flyover (see Introduction for specific flight dates), which includes raw imagery collected to support the generation of 0.5 Ft Ground Sample Distance (GSD) natural color imagery. The images were captured with 80% forward lap and side lap to support 1”=100’ mapping and meet the distortion free requirements within New York City. Planimetrics are developed to meet American Society for Photogrammetry and Remote Sensing (ASPRS) Class 1 (one) horizontal mapping standards and ASPRS vertical Class 2 (two) accuracy specifications. Planimetrics are delivered via an ESRI geodatabase in New York State Plane Coordinates, Long Island East Zone, NAD83, US foot.


# General Attribute Information

The following attribute information applies to all feature classes.  Additional attributes specific to a given feature class are listed within the details for that feature class.

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **SOURCE_ID** | Unique feature Identification Number. |
| **FEATURE_CODE** | Indicates the type of feature.  |
| **SUB_FEATURE_CODE** | (where applicable) indicates a subset of features within a given “Feature_Code” set.  |
| **STATUS** | Field indicating the feature status as it fits into one of the following categories:a) NEW. A feature captured for the first time during the 2014 planimetrics update project.b) UPDATED. The feature existed previously but has been updated during the 2014 planimetrics update project.c) UNCHANGED. The feature is unchanged from the source planimetrics database. |
[Back to Table of Contents](# table-of-contents)


# BOARDWALK

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Boardwalks along beachfront. |
| **Capture Notes** | Maintain beach outline/shoreline (do not adjust for tidal differences between imagery flyover dates). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Boardwalk](Images/FeatureViews/Boardwalk.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# BUILDING FOOTPRINT

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Building](# subtype-building)** | <p align="center">2100</p> |
| **[Sky Bridge](# subtype-skybridge)** | <p align="center">2110</p> |
| **[Building Under Construction](# subtype-building-uc-building-under-construction)** | <p align="center">5100</p> |
| **[Garage](# subtype-garage)** | <p align="center">5110</p> |

[**Attributes**](# building-footprint-attributes)

[**Diagrams**](# building-footprint-diagrams)

### Subtype: BUILDING

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.Buildng footprint database. |
| **Features Captured** | All buildings with well-defined walls and roofs that are >400 square feet and taller than 12 feet were captured.Buildings with <12 feet height but with BIN were captured.Buildings with BIN but <400 square feet were also captured. |
| **Capture Notes** | Buildings with flat roofs were captured on roof outline, capturing the largest outline (excluding overhangs, awnings, construction features, etc.).Buildings with pitched roofs were captured on the building footprint.Carports, when attached to main building, were included in the outline. Interior divisions within buildings were not captured (used existing building layer and BIN as guide).Parcel data and BIN was used as guidance for collection. Where the parcel data indicated that a building should be two or more geometries AND there was NO physical indication, the building was split using the parcel lines. Where the parcel data indicated that a building should be two or more geometries AND there was a physical indication, the building was split using the physical indications. If an existing building was split into several new buildings, the original BIN was retained in only one of the new buildings (ideally the largest) and the new buildings were assigned an "million" BIN (as a placeholder). BINs can not be duplicated. Building Footprints abutting one another on a single tax lot, but each having a unique BIN, were flagged and verified during review.If a building was demolished (i.e., as evidenced in the imagery), the BIN was also deleted and was not used for any new building geometry.Small triangles denote a permit is out to construct a new building at the location.  These small triangles were added by DoITT building editors. These triangles should be removed when new buildings are added. Therefore if a new building was constructed in the new orthos, the building was captured,  the attributes from triangle to building were transferred to the new building, and the triangle was deleted. If no new building was visible on the orthos, the triangles were left in the data.An “million" BIN was assigned to buildings not existing in the source database.For more information regarding BIN, see [Building Footprint Attributes](# building-footprint-attributes). |
| **Features Excluded** | The following features were not captured:•  temporary trailers, tents, or roofs at gas stations (over pumps).• roofs (overhang) to gas stations, unless connected to building.• movable jet bridge for access to aircraft.• awnings, scaffolds, or sidewalk sheds. |
| **Feature View** | <p align="center">![Build_Foot](Images/FeatureViews/Build_Foot.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: GARAGE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.Buildng footprint database.  DOF Digital Tax Map database |
| **Features Captured** | All garages were captured, regardless of size.  To be considered a garage, the structure must have a driveway (paved or unpaved) for road  access, and be able to store one or more cars. |
| **Capture Notes** | Special care was applied to ensure sheds were not confused with garages. In general, standard dimensions for detached garages are approximately 12’x20’ or 14’x20’.The Parcel layer was used to place garages within parcel or at parcel boundary – being sure to check for special cases where parcel boundary clearly crosses a garage. In these cases, either the garage was split using physical features, or the property line was used where there was no distinguishing physical feature.An “million" BIN was assigned to garages not existing in the source database. For more information regarding BIN, see [Building Footprint Attributes](# building-footprint-attributes). |
| **Features Excluded** | Small tool or storage sheds in backyards which have no visible car access were not captured. |
| **Feature View** | <p align="center">![Garages](Images/FeatureViews/Garages.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BUILDING U/C (Building under Construction)

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.Buildng footprint database.  DOF Digital Tax Map database |
| **Features Captured** | Buildings that were under construction in the imagery and had outside walls that clearly indicated the shape of the building were captured.An “million" BIN was assigned to buildings (under construction) not existing in the source database.  For more information regarding BIN, see [Building Footprint Attributes](# building-footprint-attributes). |
| **Capture Notes** | n/a |
| **Features Excluded** | Under construction buildings were not captured when only the foundation was visible or if the building was being destroyed. |
| **Feature View** | <p align="center">![Build_UC](Images/FeatureViews/Build_UC.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SKYBRIDGE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  PLUTO |
| **Features Captured** | Elevated walkways that connect buildings were captured as separate building polygons and coded as “Skybridge”. |
| **Capture Notes** | Skybridges were populated with the “HEIGHT_ROOF” attribute only (not Ground Elevation).These were assigned an “million" BIN during capture. For more information regarding BIN, see [Building Footprint Attributes](# building-footprint-attributes). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Skybridge](Images/FeatureViews/Skybridge.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/skybridge.jpg)</p> |
[Back to Table of Contents](# table-of-contents)


#### Building Footprint Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **HEIGHT_ROOF** | Building roof height was calculated as the difference between ground elevation of the building and the roof elevation value.  The roof elevation is the highest point of the roof itself (see [BUILDING ELEVATION](# subtype-building-elevation) in the [ELEVATION](# elevation) Feature Class). See [Building Footprint Diagrams](# building-footprint-diagrams) below for additional details. |
| **GROUND_ELEVATION** | Represents an interpolated elevation value at the centroid (center point) of the building. The process for capturing this is as follows:1. A bare-earth surface is generated from the 2010 LiDAR by first removing any points that fall within a building polygon. These points are removed to eliminate any data anomalies (e.g., points captured at the roof level). A Digital Terrain Model (DTM) is then generated from the remaining points by interpolating the elevations around the building edges to develop a continuous surface.2. Building centroids (i.e., the center point within each building) are then draped over the  DTM generated from step 1.  The bare-earth elevation value at that building centroid is then transferred to the ground elevation attribute of the building footprint.  The purpose is to determine a single elevation value that is representative of the elevation values surrounding each building.  |
| **NAME** | Name of building. |
| **BIN** | A Building Identification Number (BIN) is a unique identifier assigned by the Department of City Planning (DCP) for buildings in Geosupport. DoITT inserts assigned BINs into their respective footprints on an ongoing basis through interagency coordination. For cases where a BIN has not been assigned or cannot be determined, a "million” BIN is inserted as follows:• 1000000 for Manhattan,• 2000000 for Bronx,• 3000000 for Brooklyn,• 4000000 for Queens,• 5000000 for Staten Island |
| **CONSTURCTION_YEAR** | Derived from PLUTO. The year construction of the building was completed. See "BuiltCode" field for details on accuracy. |
| **GEOM_SOURCE** | Source for the construction of the building geometry.   |
| **LAST_MODIFY_BY** | User that last updated the geometry or attributes of a building feature. |
| **LAST_MODIFY_DATE** | Date that a building feature's geometry or attributes was last modified. |
| **LAST_STATUS_TYPE** | The status of a building - "Constructed", "Marked for Construction", or "Marked for Demolition".  |
| **DOITT_ID** | Unique numeric ID assigned by DoITT.  |
| **LAST_STATUS_DATE** | Most recent date that a building status was changed. |
| **HEIGHT_ROOF** | Building Height is calculated as the difference from the building elevation from the Elevation point feature class and the elevation in the interpolated TIN model. This value then is the height of the roof above the ground elevation, NOT its height above sea level. |
| **DOB_JOB_NUM** | Job number from DOB_JOB table obtained from milestone reports.  |
| **NUM_FLOORS** | Derived from PLUTO. Indicates the number of full and partial stories starting from the ground floor. For cases where a lot has more than one building, the number of stories in the primary building on the tax lot is applied to all buildings on the lot.|
| **BUILT_CODE** | Derived from PLUTO. A code indicating whether the year the building was built (CONSTRUCTION_YEAR) is an estimate. E = Estimate; Blank = Year Built is not an Estimate |

[Back to Table of Contents](# table-of-contents)


#### Building Footprint Diagrams
##### Calculating HEIGHT_ROOF
<p align="center">![Build_Foot_Diagram_1](Images/FeatureViews/Build_Foot_Diagram_1.png)</p>

<p align="center">![Build_Foot_Diagram_2](Images/FeatureViews/Build_Foot_Diagram_2.png)</p>


[Back to Table of Contents](# table-of-contents)


# COOLING TOWERS

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  New capture. |
| **Features Captured** | Cooling Towers found on the roofs of large buildings that enclose large fans used for ventilation and cooling. |
| **Capture Notes** | Only cooling towers greater than four (4) ft in diameter were captured. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Cooling Towers](Images/FeatureViews/CoolingTower.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# CURB

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database |
| **Features Captured** | All curbs between roadbed pavement and other surfaces (i.e., within the street right-of-way) were captured. |
| **Capture Notes** | This is a new feature class in the 2014 collection.  Prior to the 2014 capture, Curbs were a subset of the Pavement Edge feature class but have been broken out into a seperate feature class in 2014. |
| **Features Excluded** | Curbs inside Parking lots were not captured. |
| **Feature View** | <p align="center">![Curb](Images/FeatureViews/Curb.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# ELEVATION

**Geometry Type:** Point

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Building Elevation](# subtype-building-elevation)** | <p align="center">3020</p> |
| **[Water Elevation](# subtype-water-elevation)** | <p align="center">3010</p> |
| **[Spot Elevation](# subtype-spot-elevation)** | <p align="center">300000</p> |
| **[Bridge Elevation](# subtype-bridge-elevation)** | <p align="center">300020</p> |

[**Attributes**](# elevation-attributes)

[**Diagrams**](# elevation-diagrams)

*Note: The vertical accuracy was set to the following standard:  ASPRS 1”=100’ Class 2.*

### Subtype: BUILDING ELEVATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Elevation points were captured for all building footprint features. |
| **Capture Notes** | Elevation of the highest portion of the roof of a building, excluding antennas and roof fixtures such as air conditioning (AC), elevator shafts, chimneys, etc.Elevation values were transferred to each building footprint to calculate the building height attribute. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Elevation_Build](Images/FeatureViews/Elevation_Build.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: WATER ELEVATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Elevation points were captured on standing water (ponds, reservoirs, lakes). |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Elevation_Water](Images/FeatureViews/Elevation_Water.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SPOT ELEVATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Spot elevations were captured on paved, unpaved, and alley subtypes in <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> centerline and all <a href="https://data.cityofnewyork.us/dataset/Sidewalk-Centerline/a9xv-vek9/about">Interior Sideswalk CSCL</a> feature classes.  Elevation points were placed in the center of the roadbed (coincident with CSCL features).  These points were captured at the beginning, middle, and end of length of visible roadbed.  Additional elevation points were added at 200’ spacing when the distance between the beginning, middle, or end was greater than 200 linear feet. |
| **Capture Notes** | In areas where the [PAVEMENT_EDGE](# pavement_edge) feature class has been updated, any existing Spot elevations were updated.For new streets, new spot elevations were created in the center of the roadbed according to the following rules:1) Placed at Intersections (might not necessarily be at the same location as the node from the centerline, one point per intersection even on complex intersections).2) Placed Every 200 feet when midpoint of bridge or city block exceeds distance.3) Placed on paved, unpaved, alley subtypes in <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> centerline features class and all of the Interior Sidewalk Centerline feature class.  Spot elevation were not added to a CSCL feature if no roadbed exists (e,g, area is under construction).4) Mid-Street segment – at the approximate mid-point of a street segment. |
| **Features Excluded** | Spot elevations were not captured on a <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> feature if no roadbed exists. |
| **Feature View** | <p align="center">![Elevation_Spot](Images/FeatureViews/Elevation_Spot.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BRIDGE ELEVATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | This is a subset of spot elevations.  These points were captured at the beginning, middle, and end of length of visible bridges and overpasses.  Additional elevation points were added at 200’ spacing when the distance between the beginning, middle, or end was greater than 200 linear feet. |
| **Features Excluded** | Elevation points were not collected for pedestrian/bike bridges. |
| **Feature View** | <p align="center">![Elevation_Bridge](Images/FeatureViews/Elevation_Bridge.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Elevation Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **Elevation** | Field measuring surface elevation above sea level (in feet). |
[Back to Table of Contents](# table-of-contents)


#### Elevation Diagrams
<p align="center">![Elevation_Diagram](Images/FeatureViews/Elevation_Diagram_2.JPG)</p>

[Back to Table of Contents](# table-of-contents)


# HYDRO STRUCTURE

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Piers](# subtype-piers)** | <p align="center">2800</p> |
| **[Jetty](# subtype-jetty)** | <p align="center">2810</p> |
| **[Seawall](# subtype-seawall)** | <p align="center">2820</p> |

[**Attributes**](# hydro-structure-attributes)

### Subtype: PIERS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Decks supported by posts extending into the water. |
| **Capture Notes** | Updated piers, commercial piers, and docks. Used existing planimetrics data as guide. |
| **Features Excluded** | Individual/private docks for recreational watercraft were not captured, unless they had already been captured as such in existing planimetric data. |
| **Feature View** | <p align="center">![Pier](Images/FeatureViews/Pier.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: JETTY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Structures, usually comprised of stone, earth, or concrete; extending from shore to lessen erosion.  They are often installed in continuation of river channels at their outlets or into docks, and outside their entrances. |
| **Capture Notes** | Delineated at the water level. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Jetty](Images/FeatureViews/Jetty.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SEAWALL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Seawalls are typically built on the land parallel to the coast, but may also include breakwaters that are built into the water. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Seawall](Images/FeatureViews/Seawall.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Hydro Structure Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **Elevation** | Field measuring surface elevation above sea level (in feet). |
[Back to Table of Contents](# table-of-contents)


# HYDROGRAPHY

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Lake/Reservoir](# subtype-lakereservoir)** | <p align="center">2600</p> |
| **[Pond](# subtype-pond)** | <p align="center">2610</p> |
| **[River](# subtype-river)** | <p align="center">2620</p> |
| **[Stream](# subtype-stream)** | <p align="center">2630</p> |
| **[Wetland/Marsh](# subtype-wetlandmarsh)** | <p align="center">2640</p> |
| **[Beach/Shoreline](# subtype-beachshoreline)** | <p align="center">2650</p> |
| **[Bay/Ocean](# subtype-bayocean)** | <p align="center">2660</p> |

[**Attributes**](# hydrography-attributes)

### Subtype: LAKE/RESERVOIR

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated all Lake/Reservoirs when general shape had changed. Existing features were not updated due to different water level. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Lake](Images/FeatureViews/Lake.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: POND

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated pond outline when general shape had changed. Existing features were not updated due to different water level. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Pond](Images/FeatureViews/Pond.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RIVER

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated all river edges whenever new conditions were encountered (e.g., due to piers, etc.).  Maintained internal divisions of river due to name change(s).  Existing hydrographic centerlines were used as reference but were not updated. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![River](Images/FeatureViews/River.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: STREAM

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated all streams found to be wider than eight (8) feet if bank had changed.  Maintained internal divisions of stream due to name change(s). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Stream](Images/FeatureViews/Stream.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: WETLAND/MARSH

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Update wetland and marsh boundaries only when changed due to drainage, change in surface, or if covered by buildings. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Wetland](Images/FeatureViews/Wetland.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BEACH/SHORELINE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated beach and shoreline whenever feature had changed due to construction or erosion.  DoITT designation in existing files was maintained. Maintained interior divisions.  Did not update due to different water level (high/low tide). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Beach](Images/FeatureViews/Beach.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BAY/OCEAN

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | n/a |
| **Capture Notes** | Updated bay/ocean shoreline whenever feature had changed due to construction or erosion.  DoITT designation in existing files was maintained. Maintained interior divisions.  Did not update due to different water level (high/low tide). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Bay](Images/FeatureViews/Bay.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Hydrography Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **NAME** | Name of Waterbody or Watercourse. |

[Back to Table of Contents](# table-of-contents)


# MEDIAN

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Median_Painted](# subtype-median_painted)** | <p align="center">360010</p> |
| **[Median_Curb](# subtype-median_curb)** | <p align="center">360020</p> |
| **[Median_Rail](# subtype-median_rail)** | <p align="center">360030</p> |
| **[Median_Fence](# subtype-median_fence)** | <p align="center">360040</p> |
| **[Median_Grass](# subtype-median_grass)** | <p align="center">360050</p> |
| **[Median_Barrier](# subtype-median_barrier)** | <p align="center">360060</p> |

*Rule: Medians were not intersected by <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> on the same road except in some rare occasions (e.g. at street intersections with medians). Median type hierarchy is as follows: barrier, rail, fence, curb, grass and painted.*

### General Guidelines for Medians

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All medians that physically divide a roadbed were collected; which includes medians, traffic islands, "Jersey Barriers", and painted areas that are used to separate traffic flow. |
| **Capture Notes** | Medians are sometimes paved, are normally elevated (have a curb), or have dirt or grass.Medians can have sidewalks crossing them. In those cases, the outline of the largest area was incorporated into a single median feature.The NYC online <a href="https://data.cityofnewyork.us/Transportation/Bike-Routes/umu5-zyd3">Bike Routes</a> data was used as a reference to identify potential new medians. Areas where the column ALLCLASSES is equal to I and "I,II" most often contained new medians. New Medians exist throughout the City regardless of these bike lane classifications. Thus, this was considered a supplemental source only. |
| **Features Excluded** | The following features were not captured as medians:&nbsp;&nbsp;&nbsp;• Barriers in front of buildings,&nbsp;&nbsp;&nbsp;• Jersey Barriers used to regulate traffic in construction areas, or&nbsp;&nbsp;&nbsp;• Jersey Barriers used to block-off road access. |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_PAINTED

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Medians having white paved marking (fishbone or striped pattern). |
| **Capture Notes** | n/a |
| **Features Excluded** | Double yellow lines in the middle of a road were not captured as median.Single independent white medians hatching used to direct traffic were not captured as median. |
| **Feature View** | <p align="center">![Median_Painted](Images/FeatureViews/Median_Painted.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_CURB

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Medians with curb edging, regardless of interior content (grass, pavement, concrete, etc.). |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Median_Curb](Images/FeatureViews/Median_Curb.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_RAIL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Medians with guardrail outlining the curb of the median.  |
| **Capture Notes** | These features incorporate a fixed width of three (3) feet centered on the fence. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Median_Rail](Images/FeatureViews/Median_Rail.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_FENCE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Medians with fencing.   |
| **Capture Notes** | n/a |
| **Features Excluded** | If feature represents a Jersey Barrier with fencing, the feature was collected as a Jersey barrier. |
| **Feature View** | <p align="center">![Median_Fence](Images/FeatureViews/Median_Fence.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_GRASS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Medians with grass/vegetation inside and no curb. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Median_Grass](Images/FeatureViews/Median_Grass.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MEDIAN_BARRIER

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | "Jersey barriers" of a “permanent nature” (i.e., in place to regulate the traffic, positioned at a constant width of three (3) feet centered on the barrier).  |
| **Capture Notes** | Whenever two jersey barriers were placed next to or in short distance of each other, the outer-most edge of both were used to determine the outline of a single feature. |
| **Features Excluded** | Barrier medians which are moved on a daily basis, (e.g., at Manhattan entrances to Lincoln Tunnel) were not captured. |
| **Feature View** | <p align="center">![Median_Barrier](Images/FeatureViews/Median_Barrier.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# MISC STRUCT POLY

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Large Billboard and Signs](# subtype-large-billboard-and-signs)** | <p align="center">4100</p> |
| **[Sign Gantry](# subtype-sign-gantry)** | <p align="center">4110</p> |
| **[Toll Area](# subtype-toll-area)** | <p align="center">4200</p> |

[**Attributes**](# misc-struct-poly-attributes)

### Subtype: LARGE BILLBOARD AND SIGNS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All billboards (including those found on rooftops), with three (3) foot standard width. |
| **Capture Notes** | These features are represented with multiple shapes (triangle, V- shaped, etc.). |
| **Features Excluded** | Support structures were not included as part of these features. |
| **Feature View** | <p align="center">![Billboard](Images/FeatureViews/Billboard.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SIGN GANTRY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Traffic information strutures that cross traffic lanes. |
| **Capture Notes** | These features were digitized end-to-end, with seven (7) foot standard width. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Sign_Gantry](Images/FeatureViews/Sign_Gantry.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: TOLL AREA

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Roof outline of toll plaza buildings (tool booths), regardless of size. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Toll_Plaza](Images/FeatureViews/Toll_Plaza.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Misc Struct Poly Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **DESCRIPTION** | Field characterizing the miscellaneous structure. |

[Back to Table of Contents](# table-of-contents)


# OPEN SPACE

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Cemetery Outline](# subtype-cemetery-outline)** | <p align="center">2500</p> |
| **[Recreational Area](# subtype-recreational-area)** | <p align="center">2510</p> |
| **[Vacant Area](# subtype-vacant-area)** | <p align="center">2520</p> |

[**Attributes**](# open-space-attributes)

### Subtype: CEMETERY OUTLINE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated cemetery boundaries from new imagery. |
| **Capture Notes** | Individual headstones, graves, or interior boundaries were not partitioned. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Cemetery](Images/FeatureViews/Cemetery.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RECREATIONAL AREA

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Outline of recreational areas which may be used for picnic or other recreational activities. Recreational areas must contain at least one of the following:&nbsp;&nbsp;&nbsp;a) Benches,&nbsp;&nbsp;&nbsp;b) Swings, or&nbsp;&nbsp;&nbsp;c) Play areaHardscape recreational areas were collected differently than softscape recreational areas, as follows:• Hardscape recreational areas have either hard surfaces or sand. These areas were captured as discrete polygons following the edges of these areas precisely.• Softscape recreational areas are grassy areas for football/baseball/other. These areas were captured as a single polygon (i.e., not discrete polygons) and snapped to other features (e.g. sidewalks, roadbed, hydro, etc.) where applicable.When hardscapes and softscapes exists adjacent to one another, the entire area was captured by a single polygon. |
| **Capture Notes** | These features are entirely outside of NYC designated parks. |
| **Features Excluded** | Medians with either benches, swings, or play areas were captured as a median and not a recreational area. |
| **Feature Views** | <p align="center">![Recreation_Area_2](Images/FeatureViews/Recreation_Area_2.JPG)This screenshot represents a hardscape recreational area.</p><p align="center">![Recreation_Area_2](Images/FeatureViews/Recreation_Area_3.JPG)This screenshot represents a softscape recreational area.</p><p align="center">![Recreation_Area](Images/FeatureViews/Recreation_Area.JPG)This screenshot represents a combined hardscape / softscape recreational area.</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: VACANT AREA

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DOF Digital Tax Map |
| **Features Captured** | These features represent a vacant lot where a building could potentially be built and is associated with a tax lot polygon. |
| **Capture Notes** | "Vacant" is defined herein as an area containing no structures.The Digital Tax Map (DTM) and currently captured planimetrics ([Building Footprints](# building-footprints)) were used to determine the location of the vacant areas.The actual shape of each vacant aras was captured using physical features that typically form the boundary of a property such as fences, hedgerow, etc.Vacant Areas extend to sidewalk or roadbed edge.As a general rule of thumb, vacant lots were required to have roadway frontage, and not actively used for private or public entities (e.g., backyard or commmunity garden). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Vacant_Area](Images/FeatureViews/Vacant_Area.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Open Space Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **NAME** | Name of Open Space Area. |

[Back to Table of Contents](# table-of-contents)


# PARK

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Park Boundary](# subtype-park-boundary)** | <p align="center">4980</p> |
| **[Baseball/Softball Field](# subtype-baseballsoftball-field)** | <p align="center">4900</p> |
| **[Basketball Court](# subtype-basketball-court)** | <p align="center">491010</p> |
| **[Handball](# subtype-handball)** | <p align="center">491030</p> |
| **[Multipurpose Court](# subtype-multipurpose-court)** | <p align="center">491050</p> |
| **[Tennis Court](# subtype-tennis-court)** | <p align="center">491060</p> |
| **[Volleyball](# subtype-volleyball)** | <p align="center">491070</p> |
| **[Football Field](# subtype-football-field)** | <p align="center">4920</p> |
| **[Soccer Field](# subtype-soccer-field)** | <p align="center">4930</p> |
| **[Golf Course](# subtype-golf-course)** | <p align="center">4940</p> |
| **[Pools](# subtype-pools)** | <p align="center">4950</p> |
| **[Track](# subtype-track)** | <p align="center">4960</p> |
| **[Skating Rink](# subtype-skating-rink)** | <p align="center">4970</p> |
| **[Greenstreets](# subtype-greenstreets)** | <p align="center">4985</p> |

[**Attributes**](# park-attributes)

### Subtype: PARK BOUNDARY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database  Department of Parks and Recreation (DPR) Parks Properties |
| **Features Captured** | Outline the outer perimeter of any park from <a href="https://data.cityofnewyork.us/City-Government/Parks-Properties/rjaj-zgq7/about">DPR Parks Properties</a>.The boundary encompasses the entire park as a single polygon feature, regardless of special features such as baseball diamonds or tennis courts.The delineation of the outer edge of each park boundary is coincident with the “intended” boundary feature, as determined by the Parks Department. Intended boundary feature are curbs, green areas, sidewalks, etc. and vary from park to park.  At times, the intended boundary feature varies within the same park.  |
| **Capture Notes** | When the source data had a single boundary polygon extending across other planimetric features (e.g. roads), the planimetric park boundary follows the source data.When there was no apparent physical boundary feature to delineate the Park boundary, the feature was copied “as is” from the source database.Park names (SIGNNAME and source column) and park numbers (GISPROPNUM source column) were transferred from source databases to park boundaries and special features.Interior road systems and special features within parks were not partitioned. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Park](Images/FeatureViews/Park.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BASEBALL/SOFTBALL FIELD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of the sandy area (diamond) in softball/baseball fields. |
| **Capture Notes** |  These features can have different sizes and can be also be represented as painted areas on hard surfaces.These features extend back to the backstop of the field and include the 1st and 3rd base coaching boxes. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Baseball](Images/FeatureViews/Baseball.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: BASKETBALL COURT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of individual basketball courts. |
| **Capture Notes** |  These features can be represented as full or half courts. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Basketball](Images/FeatureViews/Basketball.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: HANDBALL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of handball courts. |
| **Capture Notes** | The hard surface wall was incorporated witin each court. When multiple courts are adjacent to one another, a  division line was digitized to partition individual courts. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Handball](Images/FeatureViews/Handball.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: MULTIPURPOSE COURT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of multipurpose fields. |
| **Capture Notes** |  These features are composed of mostly hard surface areas with different markings for different activities. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Court_Multipurpose](Images/FeatureViews/Court_Multipurpose.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: TENNIS COURT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of tennis courts (hard surface only). |
| **Capture Notes** | In cases of multiple courts, a division line was digitized along outer painted line (baseline and sideline) to partition individual courts.The extent of these features only includes "in-bounds areas", they do not extend to the fence surrounding the tennis court area (or related "out-of-bounds areas"). |
| **Features Excluded** | Individual tennis courts within NYC Parks were not captured.Private tennis courts (e.g., on roofs or hotels, etc.) were not captured. |
| **Feature View** | <p align="center">![Tennis](Images/FeatureViews/Tennis.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: VOLLEYBALL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of volleyball courts using distinct markings on observed hard surface. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Volleyball](Images/FeatureViews/Volleyball.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: FOOTBALL FIELD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of football fields.The extent of these features only includes "in-bounds areas", they do not extend to the turf surrounding the playing field (or related "out-of-bounds areas"). |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Football](Images/FeatureViews/Football.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SOCCER FIELD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of soccer fields. |
| **Capture Notes** |  Outline is represent by extent of grassy surface. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Soccer](Images/FeatureViews/Soccer.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: GOLF COURSE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of golf courses along fence or other man-made boundary. |
| **Capture Notes** | n/a |
| **Features Excluded** | The outline of greens, tees, fairways, sand traps, shelters, or cart paths were not captured. |
| **Feature View** | <p align="center">![Golf](Images/FeatureViews/Golf.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: POOLS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of public pool areas. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Pool](Images/FeatureViews/Pool.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: TRACK

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of running tracks, typically around grassy sport fields. |
| **Capture Notes** | n/a |
| **Features Excluded** | Tracks painted upon concrete surfaces were not captured. |
| **Feature View** | <p align="center">![Track](Images/FeatureViews/Track.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SKATING RINK

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Outline of skating/hockey rinks using distinct markings on observed hard surface. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Skating_Rink](Images/FeatureViews/Skating_Rink_2.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: GREENSTREETS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database DPR Parks Properties |
| **Features Captured** | Using <a href="https://data.cityofnewyork.us/Environment/Greenstreets/p23h-ci72">DPR Greenstreets</a> as the definitive source, these areas were updated and attributed using the source data. Name was populated from the SITENAME source column and park numbers were populated from the GISPROPNUM source column. |
| **Capture Notes** | All the rules for defining park boundaries were applied for defining Greenstreet limits. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Greenstreet](Images/FeatureViews/Greenstreet.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Park Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **PARK_NAME** | Name of Park |
| **PARKNUM** | Unique park identification number corresponding with PARK_NAME. |


[Back to Table of Contents](# table-of-contents)


# PARKING LOT

**Geometry Type:** Polygon

*Note: Parking lot outlines were often interected by sidewalks, but only at the entrance and exit.*

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All parking lots (paved or unpaved) greater than 2,000 sq. feet.Parking areas adjacent to the travel-way and separated from the travel-way by a curb or other obstruction were captured as parking lots. In these cases, the [Roadbed](# roadbed) and [Pavement Edge](# pavement-edge) end or wrap around the parking lot. The parking lot is not included as part of the Roadbed. |
| **Capture Notes** | These features connect to road edge ([Curb](# curb) or [Edge of Pavement](# subtype-edge-of-pavement)) only at entrances and exits. |
| **Features Excluded** | Traffic islands within parking lot were not captured.When a building of > 400 sq. feet was present, the building area was excluded from the parking lot polygon.Parking areas adjacent to the travel-way, but not separated from the travel-way by a curb or other obstruction, were not captured.  Instead, those parking areas were included as part of the Roadbed and the Pavement Edge extends to the outside edge of such area.Gas stations, private parking areas (e.g., for condos), and storage areas (e.g., for boats) were not captured.  |
| **Feature View** | <p align="center">![Parking_Lot](Images/FeatureViews/Parking_Lot.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# PAVEMENT EDGE

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Edge Of Pavement](# subtype-edge-of-pavement)** | <p align="center">2260</p> |
| **[Airport Runway](# subtype-airport-runway)** | <p align="center">2230</p> |
| **[Alley](# subtype-alley)** | <p align="center">2270</p> |

[**Attributes**](# pavement-edge-attributes)

[**Diagrams**](# pavement-edge-diagrams)

### Subtype: EDGE OF PAVEMENT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated all segments between pavement and other surfaces or features (i.e. Curbs, sidewalks, or grass).  |
| **Capture Notes** | Each segment was captured as a continuous feature across a blockface (typically from one intersection to the next – along that side of the road). The vertex between two segments was often located at the street corner. Edge of Pavement features are continuous across driveways, alleys, or access to parking. The one exception to this rule is where a street segment changes names (as determined by <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> Centerline names) outside of any street intersections.  In these cases, the existing CSCL break (node) was used to create corresponding breaks in Pavement Edge segments.For cul-de-sacs, two segments were created. The CSCL centerline was used to define the breakpoints of the Pavement Edge segments.Dead end streets were terminatde where the tax map crosses the road.  Two segments were created on left and right sides of CSCL.On highways, Pavement Edge corresponds to the ‘roadbed’ sub-feature class in [Roadbed](# roadbed), and does not include the shoulder. |
| **Features Excluded** | n/a |
| **Feature Views** | <p align="center">![Road_Edge](Images/FeatureViews/Road_Edge.JPG)</p>This screenshot represents pavement edges at a large intersection.</p><p align="center">![PE_culdesac](Images/FeatureViews/PE_culdesac.JPG)</p>In a cul-de-sac, two segments would be required for the edge of pavement. One on either side of the roadbed assigned a left or right side based on the CSCL.</p><p align="center">![PE_T_int](Images/FeatureViews/PE_T_int.JPG)</p>Example of a 'T' intersection, one segment would be captured for edge at the top of 'T'.</p><p align="center">![PE_name_change](Images/FeatureViews/PE_name_change.JPG)</p>For roadbeds whose street name changes, the edge of pavement should be broken/split. The Node features from CSCL can be used as a guide.</p><p align="center">![PE_interchange](Images/FeatureViews/PE_interchange.JPG)</p>For interchanges, one segment that runs between the intersections would be captured for the edge of pavement. Note that one roadbed crosses over the other as it does in reality.</p><p align="center">![PE_Alley](Images/FeatureViews/PE_Alley.JPG)</p> In the image above there are two alleys. The edge of pavement is captured as one segment between the intersections, extending over the alleys in question.</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: AIRPORT RUNWAY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | The outer-edge of all paved features associated with airports, including runways, taxiways and aprons. |
| **Capture Notes** | The features often share an edge with a building feature. Airport features were collected up to the surrounding fence or gates. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Airport](Images/FeatureViews/Airport.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: ALLEY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | These features represent a narrow unnamed street that allows access to buildings/garages other than from the road. When captured, these features were snapped to the road edge. |
| **Capture Notes** | These feature typically allow access to the interior of a block or to the back of a house.  As a general rule of thumb, the <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> value of: RW_TYPE=10 was used to determine the alley pavement edge.  However, there were still alleys captured that did not have this field attribute value from the CSCL. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Alley](Images/FeatureViews/Alley.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Pavement Edge Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **BLOCKFACEID** | Field indicates the Unique ID generated automatically.This ID was conflated to the corresponding L/R BLOCKFACEID in <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a>.See [Pavement Edge Diagrams](# pavement-edge-diagrams) for more details on conflation with special/complex scenarios. |
| **CONFLATED** | Field indicates whether or not the BLOCKFACEID value was conflated to a CSCL segment.Values are Y or N. |
[Back to Table of Contents](# table-of-contents)


#### Pavement Edge Diagrams

This section includes the following capture rules pertaining to BlockfaceID conflation from Pavement Edge to <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> for these special/complex cases:
1. [Capture Rule for missing CSCL](# 1-blockfaceid-conflation-from-pavement-edge-to-cscl---rule-for-missing-cscl)
2. [Capture Rule for Medians](# 2-blockfaceid-conflation-from-pavement-edge-to-cscl---rules-for-medians)
3. [Capture Rule for Multiple CSCL with Single Pavement Edge](# 3-blockfaceid-conflation-from-pavement-edge-to-cscl----rule-for-multiple-cscl-segments-with-a-single-pavement-edge)
4. [Capture Rule for Multiple PavementEdge with single CSCL segment](# 4-blockfaceid-conflation-from-pavement-edge-to-cscl---rule-for-multiple-pavement-edge-with-single-cscl-segment)
5. [Capture Rule for handling complex intersection/median/bridge scenarios](# 5-blockfaceid-conflation-from-pavement-edge-to-cscl---rule-for-handling-complex-intersectionmedianbridge-scenarios)


##### 1. BlockfaceID conflation from Pavement Edge to CSCL - Rule for missing CSCL

• If no <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> feature existed on an existing roadbed with Pavement Edge, the production team broke down the Pavement Edge as needed on the approximated center of where a CSCL Centerline theoretically might go.  The team then assigned Left and Right (L/R) BlockfaceIDs to the Pavement Edge.  However, these BlockfaceIDs were not conflated to any CSCL segments (and these Pavement Edge features were flagged as having a BlockfaceID that was not conflated to CSCL).

**The following are examples of where CSCL is missing and PavementEdge exists.**

<p align="center">![PE_Diagram_1_1](Images/FeatureViews/PE_Diagram_1_1.png)</p>

<p align="center">![PE_Diagram_1_2](Images/FeatureViews/PE_Diagram_1_2.png)</p>

[Back to Table of Contents](# table-of-contents)



##### 2. BlockfaceID conflation from Pavement Edge to CSCL - Rules for Medians

• When a <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> segment is bounded on one or both sides by a median, the longest edges of median Pavement Edge were assigned BlockfaceIDs, which were conflated onto applicable adjacent CSCL segments.
• Assigned BlockfaceIDs to Pavement Edge for all medians except painted medians.
• Conflated to CSCL where no Pavement Edge derived BlockfaceID takes priority, and there was a CSCL segment that corresponded to the long edge of the median.
• In cases where medians are within medians, the conflating median is the majority (containing) median.
• Pavement Edge features on a median were flagged as having a BlockfaceID that was not conflated to CSCL.

<p align="center">![PE_Diagram_2_1](Images/FeatureViews/PE_Diagram_2_1.png)</p>

<p align="center">![PE_Diagram_2_2](Images/FeatureViews/PE_Diagram_2_2a.JPG)</p>

<p align="center">![PE_Diagram_2_3](Images/FeatureViews/PE_Diagram_2_3.png)</p>

[Back to Table of Contents](# table-of-contents)



##### 3. BlockfaceID conflation from Pavement Edge to CSCL -  Rule for Multiple CSCL Segments with a Single Pavement Edge

• In cases where there are multiple <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> segments running along a single Pavement Edge (median or otherwise), the BlockfaceID from the Pavement Edge was conflated to the CSCL segments that correspond to the single Pavement Edge.

<p align="center">![PE_Diagram_3](Images/FeatureViews/PE_Diagram_3.png)</p>

[Back to Table of Contents](# table-of-contents)



##### 4. BlockfaceID conflation from Pavement Edge to CSCL - Rule for Multiple Pavement Edge with single CSCL segment

• In cases where multiple Pavement Edge segments span a single <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> (median or otherwise), only the BlockfaceID from the Pavement Edge closest to the CSCL segment midpoint was transferred to CSCL.  The other BlockfaceIDs were not conflated to CSCL. An attribute was added to the Pavement Edge database that indicates whether or not each BlockfaceID had been associated with a CSCL segment.

<p align="center">![PE_Diagram_4_1](Images/FeatureViews/PE_Diagram_4_1.png)</p>

<p align="center">![PE_Diagram_4_2](Images/FeatureViews/PE_Diagram_4_2.png)</p>

[Back to Table of Contents](# table-of-contents)



##### 5. BlockfaceID conflation from Pavement Edge to CSCL - Rule for handling complex intersection/median/bridge scenarios

• In cases of complex intersections with multiple medians and/or elevated roadways/bridges, each level was evaluated individually (i.e., at grade, elevated, etc.) in order to logically determine the appropriate break points on medians and to assign BlockfaceIDs to the correct <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a>. The use of Pavement Edge’s polylineZ information and the use of CSCL’s “level codes” were used to determine which features are on the same vertical plane.
• Only the “straight edges” of medians were assigned to CSCL segments.  Small corner segments for triangular medians were not created.

**The screenshot below shows an example of a “complex” intersection.**

<p align="center">![PE_Diagram_5_1](Images/FeatureViews/PE_Diagram_5_1.png)</p>

**The screenshot below is the same intersection, but showing only the “at grade” centerlines and Pavement Edgs/Median features. Arrows have been included to depict the assignment of L/R BlockfaceIDs for the “at grade” segments in this intersection.**

<p align="center">![PE_Diagram_5_2](Images/FeatureViews/PE_Diagram_5_2.png)</p>

[Back to Table of Contents](# table-of-contents)


# PLAZA

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Plazas are hard surfaced "parks" adjacent to public sidewalks or pavement edges. |
| **Capture Notes** | All public space plazas were captured or updated.  Where a plaza is connected to a sidewalk by steps, the steps were considered to be part of the plaza polygon. Planters at the edge of plaza were included as part of the plaza boundary.  Plazas cannot overlap medians or sidewalks. Walkways within the plaza were captured as part of the overall plaza polygon and were not considered a separate polygon. Additionally, potential plazas were also identified using <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about/">CSCL</a> (TRAFDIR=NV and BIKE_LANE<>1), to find plazas in and around greenways. |
| **Features Excluded** | Private plazas were not captured using maps showing <a href="http://www1.nyc.gov/assets/planning/download/pdf/plans/pops-inventory/pops-inventory.pdf">Privately Owned Public Space ("POPS")</a>. |
| **Feature View** | <p align="center">![Plaza_2](Images/FeatureViews/Plaza_2.JPG)</p>Example of Plaza showing vegetated area captured – adjacent to sidewalk.<p align="center">![Plaza_3](Images/FeatureViews/Plaza_3.JPG)</p>Example of large Pedestrian Plaza that was formerly a roadbed. |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# RAILROAD

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Railroad](# subtype-railroad)** | <p align="center">2400</p> |
| **[Elevated Railroad](# subtype-elevated-railroad)** | <p align="center">2410</p> |
| **[Embankment Railroad](# subtype-embankment-railroad)** | <p align="center">2420</p> |
| **[Viaduct Centerline](# subtype-viaduct-centerline)** | <p align="center">2430</p> |
| **[Open Cut Depression Railroad](# subtype-open-cut-depression-railroad)** | <p align="center">2440</p> |
| **[Railway Fence](# subtype-railway-fence)** | <p align="center">2450</p> |
| **[Abandoned Railroad](# subtype-abandoned-railroad)** | <p align="center">2465</p> |

[**Attributes**](# railroad-attributes)

### Subtype: RAILROAD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated railroad centerlines. |
| **Capture Notes** | All visible railroad centerlines were collected/updated.Hidden railroad centerlines (in tunnels) were copied from existing data with no elevation value or change. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR](Images/FeatureViews/RR.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: ELEVATED RAILROAD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated elevated railroad centerlines. |
| **Capture Notes** | No elevation value was calculated. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Elevated_RR](Images/FeatureViews/Elevated_RR.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: EMBANKMENT RAILROAD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated embankment railroad centerlines. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Embankment_RR](Images/FeatureViews/Embankment_RR.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: VIADUCT CENTERLINE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated viaduct railroad centerlines. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Viaduct_RR](Images/FeatureViews/Viaduct_RR.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: OPEN CUT DEPRESSION RAILROAD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated open cut depression railroad centerlines. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Depression_RR](Images/FeatureViews/Depression_RR.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RAILWAY FENCE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated open railway fence lines. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Railway_Fence](Images/FeatureViews/Railway_Fence.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: ABANDONED RAILROAD

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated abandoned railroad centerlines. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Abandoned_RR](Images/FeatureViews/Abandoned_RR.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Railroad Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **NAME** | Name of Railroad. |

[Back to Table of Contents](# table-of-contents)


# RAILROAD STRUCTURE

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Subway/Train Station](# subtype-subwaytrain-station)** | <p align="center">2160</p> |
| **[Elevated Subway/Train Station](# subtype-elevated-subwaytrain-station)** | <p align="center">2140</p> |
| **[Ventilation Grate](# subtype-ventilation-grate)** | <p align="center">2470</p> |
| **[Emergency Exit](# subtype-emergency-exit)** | <p align="center">2480</p> |
| **[Transit Entrance](# subtype-transit-entrance)** | <p align="center">2485</p> |

[**Attributes**](# railroad-structure-attributes)

### Subtype: SUBWAY/TRAIN STATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated all stand-alone subway and train stations, and their platforms. These structures were found on terrain level or lower. |
| **Capture Notes** | Roof outlines were delineated to include any underlying stairways. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_sta](Images/FeatureViews/RR_sta.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: ELEVATED SUBWAY/TRAIN STATION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated all elevated subway and train stations, and their platforms. |
| **Capture Notes** | Roof outlines were delineated to include any underlying stairways. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_Elev_sta](Images/FeatureViews/RR_Elev_sta.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: VENTILATION GRATE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Ventilation grates were be captured throughout the city. |
| **Capture Notes** | These locations are not dependent on vicinity to subway centerline or subway entrance / exit. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_Vent](Images/FeatureViews/RR_Vent.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: EMERGENCY EXIT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated all emergency exits on railroad structures. |
| **Capture Notes** | Usually identified as painted yellow plates/grates for subways. Used ROW of existing subway centerlines as guide. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_Exit](Images/FeatureViews/RR_Exit.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: TRANSIT ENTRANCE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Updated all transit entrances.  |
| **Capture Notes** | Usually identified as painted stairs for subways.  Used ROW of existing subway centerlines as guide. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_Entrance](Images/FeatureViews/RR_Entrance.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Railroad Structure Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **NAME** | Name of Railroad. |

[Back to Table of Contents](# table-of-contents)


# RETAINING WALL

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Retaining Wall](# subtype-retaining-wall)** | <p align="center">4000</p> |
| **[Railroad Retaining Wall](# subtype-railroad-retaining-wall)** | <p align="center">2460</p> |


### Subtype: RETAINING WALL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Walls built to retain earth from falling on transportation features with a height of ten (10) feet or greater. |
| **Capture Notes** | n/a |
| **Features Excluded** | Walls in backyards used for landscape were not captured.Walls in areas under construction (excavation) were not captured. |
| **Feature View** | <p align="center">![Retaining_Wall_1](Images/FeatureViews/Retaining_Wall_1.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RAILROAD RETAINING WALL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Walls built to retain earth from falling on railroad bed. |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Retaining_Wall_2](Images/FeatureViews/Retaining_Wall_2.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# ROADBED

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Roadbed](# subtype-roadbed)** | <p align="center">350000</p> |
| **[Intersection](# subtype-intersection)** | <p align="center">350010</p> |
| **[Driveway](# subtype-driveway)** | <p align="center">350030</p> |
| **[Shoulder](# subtype-shoulder)** | <p align="center">350020</p> |


### Subtype: ROADBED

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Roadbed represents the interior polygon of pavement edge. The edges of these features are coincident with the linear feature class [Pavement Edge](# pavement-edge). |
| **Capture Notes** | Converging roadbeds were not split when it crossing one another at different elevations (e.g. on ramps that cross each other). Roadbed was usually cut by [Median](# median) features (e.g., curb & grass) with the exception of painted, barrier and fence medians.Special care was applied to ensure that highway shoulders were not confused as sidewalk features. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Roadbed](Images/FeatureViews/Roadbed.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: INTERSECTION

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Portion of roadbed where three (3) or more roadways meet up with one another.  Intersections were composed using features compiled and updated in [Pavement Edge](# pavement-edge). |
| **Capture Notes** | Special care was applied at intersections with a slight offset to ensure that such areas were captured and attributed as an intersection.The location where two alleys meet is considered an intersection and was captured as intersection roadbed.Intersection polygons were created by establishing the shortest distance from the intersection node to [**Pavement Edge**](# pavement-edge). |
| **Features Excluded** | When two (2) roadways form a “T”, the ending road was closed off so that the continuing roadbed edge forms a straight line (in [Pavement Edge](# pavement-edge)). Note, these "T" locations were not captured as intersection roadbed. |
| **Feature View** | <p align="center">![Intersection](Images/FeatureViews/Intersection.JPG)</p>The image above represents a typical, four (4) way intersection.<p align="center">![Intersection_3way](Images/FeatureViews/Intersection_3way.JPG)</p>The image above represents a three (3) way intersection. |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: DRIVEWAY

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All driveways > 200 feet in length and a minimum width of eight feet.  |
| **Capture Notes** | These driveways may service one or multiple buildings and there is no distiction between paved or unpaved surfaces. Driveways were compiled from [Pavement Edge](# pavement-edge).Since Driveways have centerlines, if the corresponding <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> has a name, that name is part of the main roadbed feature code. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Driveway](Images/FeatureViews/Driveway.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: SHOULDER

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All shoulders on the roadway that may be used as a “break-down” area for vehicles or used by emergency vehicles to pass traffic. Shoulders are paved or gravel areas outside of the travel lane (as determined by paint markings) suitable for emergency vehicles to pass. |
| **Capture Notes** | Shoulders were collected along highways (as determined by <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> “RW_TYPE” = 2, 3, or 9 and excluding “SEGMENT_TYPE" = G or F.) only. A curb separating an elevated paved surface from the roadway and between the roadway and a barrier median is a shoulder. Painted areas are considered shoulders. Should a painted shoulder area be tapered, the entire shoulder was captured as long as the shape was at least 8 feet wide. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Shoulder](Images/FeatureViews/Shoulder.JPG)</p>The image above represents shoulder alonge the north side of a highway.<p align="center">![Shoulder_2](Images/FeatureViews/Shoulder_2.JPG)</p>Example of Shoulder separated from the primary roadbed by a curb (top) and a gravel break-down area (bottom).<p align="center">![Shoulder_3](Images/FeatureViews/Shoulder_3.JPG)</p>Example of roadways with a shoulder and roadways with an extended roadbed.<p align="center">![Shoulder_4](Images/FeatureViews/Shoulder_4.JPG)</p>Examples of Shoulders separated by the travel way by pavement markings. Shoulder must be as wide as a car. |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# SHORELINE

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Significant changes (longer than 10 feet) along shorelines were updated to reflect new conditions. |
| **Capture Notes** | Not updated when existing shoreline follows the general shape of the shoreline in the imagery, but is offset due to tidal conditions.Streams greater than 8 feet that intersect bay/ocean were considered as part of the shoreline.  When such conditions exist, those features were used and combined with [Hydrography](# hydrography). |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Shoreline](Images/FeatureViews/Shoreline.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# SIDEWALK

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Row Sidewalk](# subtype-row-sidewalk)** | <p align="center">380000</p> |
| **[Interior Sidewalk](# subtype-interior-sidewalk)** | <p align="center">380010</p> |


### Subtype: ROW SIDEWALK

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All paved sidewalks that are located within the ROW (i.e. building to building). |
| **Capture Notes** | In areas of construction, sidewalks were collected along an imaginary line to complete polygon.In areas where equipment is stored or installed on sidewalk, the full extent of sidewalk was approximated.In areas where protection or scaffolding (pedestrian protection from overhead construction) is placed over sidewalk, sidewalk remained unchanged from existing data (not updated).Sidewalks were collected when crossing large medians or traffic islands.Sidewalks overlap the exit and entrance portion(s) of parking lot features.Sidewalks overlap driveways, but not alleys. Sidewalk will be continued under bridges and overpasses if they are visible on both sides of the structure. |
| **Features Excluded** | Openings in sidewalk (for landscaping and trees) were ignored.Large, paved open spaces in front of buildings and outside of the public ROW (may have trees and landscaping) will be included in [Plaza](# plaza) and were not captured as sidewalk. |
| **Feature View** | <p align="center">![Sidewalk_1](Images/FeatureViews/Sidewalk_1.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: INTERIOR SIDEWALK

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database</br><a href="https://data.cityofnewyork.us/Housing-Development/Map-of-NYCHA-Developments/i9rv-hdr5/about">NYCHA Development</a></br><a href="https://data.cityofnewyork.us/City-Government/Parks-Properties/rjaj-zgq7/about">DPR Parks Properties</a></br><a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a></br>Forts</br><a href="https://data.cityofnewyork.us/Health/NYC-Health-and-Hospitals-Corporation-Facilities/ymhw-9cz9/about">Hospitals</a></br>School |
| **Features Captured** | All paved sidewalks that are located outside of the ROW. |
| **Capture Notes** | Interior sidewalks followed the same general capture rules as other sidewalk features. These features were captured in the following areas: &nbsp;&nbsp;&nbsp;1. NYC Parks&nbsp;&nbsp;&nbsp;2.  NYCHA Properties&nbsp;&nbsp;&nbsp;3.  Other Residential areas&nbsp;&nbsp;&nbsp;4.  Hospital campuses&nbsp;&nbsp;&nbsp;5.  School campuses&nbsp;&nbsp;&nbsp;6.  Federal FortsThe business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel. |
| **Features Excluded** | Openings in sidewalk (for landscaping and trees) were ignored.Since the intended purpose of such features is to support emergency through travel, any spurs or dead-ends (e.g., walkways leading to a building) were not captured.These features were not captured in office parks or other similar commercial areas. |
| **Feature View** | <p align="center">![Sidewalk_2](Images/FeatureViews/Sidewalk_2.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# SIDEWALK CENTERLINE

**Geometry Type:** Polyline

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | These featuers represent interior sidewalk centerlines for all interior sidewalk polygon features (not for the ROW Sidewalk). |
| **Capture Notes** | The business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel. Interior Sidewalk Centerlines were extended beyond the Interior Sidewalk Polygons when connecting to a <a href="https://data.ny.gov/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b/about">CSCL</a> feature. |
| **Features Excluded** | [ROW Sidewalks.](# subtype-row-sidewalk) |
| **Feature View** | <p align="center">![Sidewalk_ln](Images/FeatureViews/Sidewalk_ln.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)



# SWIMMING POOL

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All in-ground swimming pools, regardless of the shape, on the inside (water) of the pool. |
| **Capture Notes** | n/a |
| **Features Excluded** | Round above-ground swimming pools and pools on buildings were not captured.Fish ponds,  landscape ponds of irregular shape, and low-sided kiddie pools were not collected.  |
| **Feature View** | <p align="center">![Swimming_Pool](Images/FeatureViews/Swimming_Pool.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


# TRANSPORT STRUCTURE

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| <p align="center">**Subtype**</p> | <p align="center">**Feature Code**</p> |
| **[Bridge](# subtype-bridge)** | <p align="center">2300</p> |
| **[Tunnel](# subtype-tunnel)** | <p align="center">2310</p> |
| **[Rail Bridge](# subtype-rail-bridge)** | <p align="center">2320</p> |
| **[Pedestrian/Bike Bridge](# subtype-pedestrianbike-bridge)** | <p align="center">2330</p> |
| **[Railroad Viaduct](# subtype-railroad-viaduct)** | <p align="center">2340</p> |
| **[Overpass](# subtype-overpass)** | <p align="center">2350</p> |

[**Attributes**](# transport-structure-attributes)

### Subtype: BRIDGE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Structures erected over obstacles for road traffic (road, railroad, hydrography). Bridge deck outlined from joint to joint when on-and off-ramp(s) are on ground.  Large bridges with on-ramps and off-ramps were collected from bridge elevation points ([Bridge Elevation](# subtype-bridge-elevation)). |
| **Capture Notes** | Features can overlap so that bridge is not split where it crosses another bridge feature. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Bridge](Images/FeatureViews/Bridge.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: TUNNEL

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Used tunnel portal to digitize. |
| **Capture Notes** | Maintained delineation from existing data when available. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Tunnel](Images/FeatureViews/Tunnel.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RAIL BRIDGE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Structure erected over obstacle for railroad traffic (road, railroad, hydrography). |
| **Capture Notes** | n/a |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Rail_Bridge](Images/FeatureViews/Rail_Bridge.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: PEDESTRIAN/BIKE BRIDGE

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Strutures allowing pedestrians/bicycles to cross transportation features.  |
| **Capture Notes** | Where applicable, outline includes stairs.  Can connect between buildings (snapped to building footprint). |
| **Features Excluded** | Skybridges connecting buildings were collected as buildings. |
| **Feature View** | <p align="center">![Ped_Bridge](Images/FeatureViews/Ped_Bridge.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: RAILROAD VIADUCT

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Bridge composed of several small arches, mostly over water. |
| **Capture Notes** | Visible changeover from solid ground to viaduct is outlined. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![RR_Viaduct](Images/FeatureViews/RR_Viaduct.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


### Subtype: OVERPASS

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | Structure erected over road, whereas the lower road has been excavated and has retaining walls on the side. |
| **Capture Notes** | Overpass is at terrain level. |
| **Features Excluded** | n/a |
| **Feature View** | <p align="center">![Overpass](Images/FeatureViews/Overpass.JPG)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)


#### Transport Structure Attributes

|     |     |
| --- | --- |
| <p align="center">**Attribute**</p> | <p align="center">**Description**</p> |
| **NAME** | Name of Transportation Structure. |

[Back to Table of Contents](# table-of-contents)


# UNDER CONSTRUCTION

**Geometry Type:** Polygon

|     |     |
| --- | --- |
| **Sources** | Current imagery - see intro for specific dates.  Previous planimetric database </br> |
| **Features Captured** | All areas under construction (excavation) or deposits of material (storage) at their outer boundary. |
| **Capture Notes** | Entrance to construction site was ignored and not snapped to sidewalk nor pavement edge. |
| **Features Excluded** | Building foundations or partially demolished buildings were not collected.Individual excavation or deposit areas were not partitioned. |
| **Feature View** | <p align="center">![Unk_Construction](Images/FeatureViews/Unk_Construction.png)</p> |
| **Photo** | <p align="center">![](Images/Photos/)</p> |
[Back to Table of Contents](# table-of-contents)
