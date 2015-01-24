## Glossary

This section contains explanations of common terms referenced in this CHHS Open Data Handbook. 

### API

An application programming interface, which is a set of definitions of the ways one piece of computer software communicates with another. It is a method of achieving abstraction, usually (but not necessarily) between higher-level and lower-level software.

### California Public Records Act

The California Public Records Act (Statutes of 1968, Chapter 1473; currently codified as California Government Code §§ 6250 through 6276.48) was a law passed by the California State Legislature and signed by the Governor in 1968. The law defines what state and local government records are open to public inspection.

### Catalog

A catalog is a collection of data tables or web services.

### CSV

A comma separated values (CSV) file is a computer data file used for implementing the organizational tool, the Comma Separated List. The CSV file is used for the digital storage of data structured in a table of lists form. Each line in the CSV file corresponds to a row in the table. Within a line, fields are separated by commas, and each field belongs to one table column. CSV files are often used for moving tabular data between two different computer programs (like moving between a database program and a spreadsheet program).

### Data

A set of values (data points) representing a specific concept or concepts. Data include, but are not limited to, 1) geospatial data 2) unstructured data, and 3) structured data.

### Database

A collection of data stored according to a schema such that a computer can easily find the desired information.

### Dataset

An organized collection of related data records maintained on a storage device, with the collection containing data organized or formatted in a specific or prescribed way, often in tabular form. In this handbook the dataset refers to the master, primary, or original authoritative collection of the data (herein synonymous with database).

### Data Steward

### The data steward is the person who has the greatest familiarity with and knowledge of the data table, the data it contains, and the purpose for the collection of the data. The data steward should know the accuracy and currency of the data, and be best able to supply metadata elements describing the data.

### Data Table

A data table, in this handbook, refers to a subset of the dataset which may include a selection and/or aggregation of data from the original dataset.

### Geographic Information System (GIS)

### A geographic information system (GIS) is a computer system designed to capture, store, manipulate, analyze, manage, and present all types of geographical data allowing the user to question, analyze, and interpret data to understand relationships, patterns, and trends.

### Information

Information means any communication or representation of knowledge such as facts, data, or opinions in any medium or form, including textual, numerical, graphic, cartographic, narrative, or audiovisual forms.

### JSON

JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for both humans to read and write and machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

### Machine-Readable File

Refers to information or data that is in a format that can be easily processed by a computer without human intervention while ensuring no semantic meaning is lost.

### Metadata

To facilitate common understanding, a number of characteristics, or attributes, of data are defined. These characteristics of data are known as "metadata," that is, "data that describes data." For any particular datum, the metadata may describe how the datum is represented, ranges of acceptable values, its relationship to other data, and how it should be labeled. Metadata also may provide other relevant information, such as the responsible steward, associated laws and regulations, and access management policy. Each of the types of data described above has a corresponding set of metadata. Two of the many metadata standards are the Dublin Core Metadata Initiative (DCMI) and Department of Defense Discovery Metadata Standard (DDMS). The metadata for structured data objects describes the structure, data elements, interrelationships, and other characteristics of information, including its creation, disposition, access and handling controls, formats, content, and context, as well as related audit trails. Metadata includes data element names (such as Organization Name, Address, etc.), their definition, and their format (numeric, date, text, etc.). In contrast, data is the actual data values such as the "US Patent and Trade Office" or the "Social Security Administration" for the metadata called "Organization Name." Metadata may include metrics about an organization's data including its data quality (accuracy, completeness, etc.).

### Public Records Act (PRA) Request

### The process by which the public requests state or local government records.

### Publishable State Data

### A data table that meets one of the following criteria: (1) data that are public by law such as via the Public Records Act or (2) the data are not prohibited from being released by any laws, regulations, policies, rules, rights, court order, or any other restriction. Data shall not be released if it is highly restricted due to HIPAA, state, or federal law. 

### RDF

Resource Description Framework - a family of specifications for a metadata model. The RDF family of specifications is maintained by the World Wide Web Consortium (W3C). The RDF metadata model is based upon the idea of making statements about resources in the form of a subject-predicate-object expression…and is a major component in what is proposed by the W3C's Semantic Web activity: an evolutionary stage of the World Wide Web in which automated software can store, exchange, and utilize metadata about the vast resources of the Web, in turn enabling users to deal with those resources with greater efficiency and certainty. RDF's simple data model and ability to model disparate, abstract concepts has also led to its increasing use in knowledge management applications unrelated to Semantic Web activity.

### RSS

A family of web feed formats (often dubbed Really Simple Syndication) used to publish frequently updated works — such as blog entries, news headlines, audio, and video — in a standardized format. An RSS document (which is called a "feed," "web feed," or "channel") includes full or summarized text, plus metadata such as publishing dates and authorship.

### Schema

An XML schema defines the structure of an XML document such as which data elements and attributes can appear in a document; how the data elements relate to one another; whether an element is empty or can include text; which types of data are allowed for specific data elements and attributes; and what the default and fixed values are for elements and attributes. A schema is also a description of the data represented within a database. The format of the description varies but includes a table layout for a relational database or an entity-relationship diagram. It is method for specifying constraints on XML documents.

### Shapefile

A shapefile is a digital vector (non-topological) storage format for storing geometric location and associated attribute information and is widely used in GIS software. It stores map (geographic) features and attribute data as a collection of files having the same prefix and the following file extensions:

- ..shp - the file that stores the feature geometry. Required. 
- ..shx - the file that stores the index of the feature geometry. Required. 
- ..dbf - the dBASE file that stores the attribute information of features. Required. 
- ..sbn and .sbx - the files that store the spatial index of the features. Optional.
- ..fbn and .fbx - the files that store the spatial index of the features for shapefiles that are read-only. Optional.
- ..ain and .aih - the files that store the attribute index of the active fields in a table or a theme's attribute table. Optional.
- ..prj - the file that stores the coordinate system information. Optional.
- ..xml - metadata for using shapefiles on the Internet. Optional. 

Since a shapefile is non-topological it does not maintain spatial relationship information such as connectivity, adjacency, and area definition. This makes the format simpler but less capable when performing complex spatial analysis.

**Small Cell Size**    

In the context of aggregated data, an aggregate number that carries a risk of re-identification due to the collection of personally identifiable information in small geographic and/or temporal units, resulting in very low counts in health or demographic data. For example, an aggregate count of 2 preterm births among Asian mothers in a small population has effectively revealed those individuals if they are the only two Asian women in the population. There is no universal standard as to what number constitutes a small cell size.

### Unstructured Data

Data that is more free-form, such as multimedia files, images, sound files, or unstructured text. Unstructured data does not necessarily follow any format or hierarchical sequence, nor does it follow any relational rules. Unstructured data refers to masses of (usually) computerized information which do not have a data structure which is easily readable by a machine. Examples of unstructured data may include audio, video and unstructured text such as the body of an email or word processor document. Data mining techniques are used to find patterns in, or otherwise interpret, this information.

### XML

Extensible Markup Language (XML) is a flexible language for creating common information formats and sharing both the format and content of data over the Internet and elsewhere.
