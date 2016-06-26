---
layout: page
title: 5. Use
permalink: /use/
---

## Public Use of the CHHS Open Data Portal

The following section describes what the public will view and how the public will be able to use the CHHS Open Data Portal.

### Public Input

The CHHS Open Data Portal encourages citizen engagement and participation through the website. The portal provides the capability by which the public can engage via the following mechanisms: (1) a survey tool asking for feedback about the website usability and data resources, (2) a dedicated email address by which the public can submit feedback or suggest specific datasets to publish, (3) an opportunity to join the Open Data listserv to receive updates about CHHS Open Data, and (4) a showcase page where useful visualizations and applications created by users can be highlighted.

### Data Tables

The CHHS Open Data Portal supports two classifications of data tables: tabular and geospatial. A tabular data table is a flat file that conforms to a predefined schema. The schema defines the characteristics of a fixed number of columns, including the column name and data type. A geospatial data table contains information that can be readily rendered on an underlying map. Examples of geospatial features include points (buildings), polylines (bus routes), and polygons (school districts), along with attribute information that describes characteristics of each spatial feature.

#### Tabular

Data tables can be exported for download in popular human-readable formats, machine-readable standards and streamable file formats. The CHHS Open Data Portal currently supports the following exportable tabular file formats:

- CSV
- JSON
- PDF
- RDF
- RSS
- XLS
- XLSX
- XML

#### Geospatial

Geospatial data contain geographic feature and attribute data that define the properties of geographic features which may be used in a geographic information system (GIS). Attributes are stored in a tabular format with unique key references to the associated geographic features. Two export methodologies are supported for geographic information: geospatial and attribute. Attribute layers can be exported as tabular data file formats (see tabular formats listed above). Geospatial data can be downloaded in any of the tabular formats defined above, as well as the following formats:

- .Shapefile
- .Keyhole Markup Language (KML/KMZ)

#### Large Files

Public data often consist of historical archives, comprised of potentially millions of records collected over an extended period of time. The CHHS Open Data Portal supports the loading, exporting and visualization of large data tables (> 1GB).

### Application Program Interface (API)

The CHHS Open Data Portal provides an open, standards-based application programming interface (API) to offer automatic access to the published data tables within the open data catalog. The portal's APIs allow the end user to get results back in JSON, XML, RSS, etc. This separation of data model and encoding allows the support of many different encoding standards, even ones that do not yet exist. This enables users to access data in a host of different file formats that are independent of the original format of the data.

#### Access to Data Tables

The CHHS Open Data Portal supports the use of an API Strategy that allows the developer community to dynamically query a data table within the data catalog. Each hosted data table within the data catalog will:

- be readily and uniformly accessible
- be available for automated processing by applications and systems
- have a standard API endpoint

All communication with the API is done through an HTTPS protocol. The portal provides the following preferred response types which are made available by specifying the format as part of the URL, or by sending the appropriate HTTP "Accepts" header:

- JSON
- XML
- CSV
- RDF

#### Featured API Catalog

Additionally, the CHHS Open Data Portal supports the creation of a featured API Catalog that provides custom endpoints to the developer community to dynamically query the data table based on "specified" data table elements. Just like published data tables, the featured API Catalog is categorized and tagged using the common domain and metadata schema. Additional information about the Socrata Open Data API can be found at [http://dev.socrata.com/](http://dev.socrata.com/).

### Terms of Use

The Open Data Portal Terms of Use are subject to modification as conditions warrant. When the Terms of Use change, this will be indicated within the Terms themselves with notification of the "Last Modified Date." Therefore, users are required to review the Terms of Use each time they use the CHHS Open Data Portal for any changes since their last visit. The Terms of Use will always be available on the landing page of the CHHS Open Data Portal.

- [CHHS Open Data Portal Terms of Use](https://chhs.data.ca.gov/terms)

## Use of Data to Develop Mobile Applications

Developers and the public are encouraged to develop applications that utilize the data on the CHHS Open Data Portal. The state may post links to some of these on the CHHS Open Data Portal, but will not generally be able to evaluate the content, accuracy, or functionality of these mobile applications.

<!-- Pagination -->
<div class="pagination">
  <a class="pagination-item older" href="{{ site.baseurl }}/disclosure">&laquo; Prev</a>
  <a class="pagination-item newer" href="{{ site.baseurl }}/glossary">Next &raquo;</a>
</div>
