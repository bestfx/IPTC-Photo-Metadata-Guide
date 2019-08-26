## Other Things Shown in the Image
IPTC supports metadata about typically annotated things in an image:

* Organisations
* Events covered by the image
* Products
* Artwork or objects in an image

> Read about metadata for specific content on pages about [general image content](how-to-edit-metadata/general-image-content.md), [persons](how-to-edit-metadata/persons-depicted-in-the-image.md) or [locations](how-to-edit-metadata/locations.md).

### Organisations (including companies) featured by the image
Featured organisations can be described by name and code:
* **Featured Organisation Name**\
The name of the organisation or company featured in or associated with the image. For example, an image of people at an event may list the organising or sponsoring company as a featured organisation.
* **Featured Organisation Code**\
A code from a known controlled vocabulary for identifying the organisation or company featured in the image. E.g. The stock ticker symbol would list Microsoft as MSFT or Adobe as ADBE. The code is not linked in this field specifically to the Organisation Name in the data structure, but it serves as an additional search term if necessary.

### Event
The Event field describes a specific named event associated with the image, e.g. Archimedes press conference, The Great Steamboat Race, Maui Classical Music Festival. Sub events of larger events can be included as in: XXXI Olympic Summer Games (Rio): opening ceremony.

### Product
The Product Shown field structure is used to describe one to many products depicted by the image. The name of the product and a textual description can be applied to the corresponding fields. To identify the product a 14 digit GTIN (Global Trade Item Number) of the product should be applied to the GTIN field, GTIN-8 to GTIN-14 codes can be used.

### Artwork or Object in the Image
This field structure is used to record information about artworks or other objects in the image, and includes descriptive, administrative and rights information. This category covers paintings, sculptures, objects, and other items of interest for cultural heritage such as archaeological finds.
* **Title (AO)**\
The textual title of the work, or reference name. Do not confuse this with the Title field for the image showing this artwork or object.
* **Content Description (AO)**\
Free-text description of the content depicted in the artwork or object e.g. View of the Rhine River in Cologne.
* **Contribution Description (AO)**\
Contributions made to the artwork or object expressed as free-text. This can include find, restoration, engraving, or any contribution not included under the work ‘Creator’. Include the type, date and location of contribution, and details about the contributor.
* **Physical Description  (AO)**\
The physical characteristics of the artwork or object as free-text. Object type, materials-techniques and measurements may be described but not content of the artwork or object, for which there is the Content Description field.
* **Date Created (AO)**\
The date (and optionally the time) that artworks or objects in the image were created. Please note that historical dates (before about 1900) may be handled differently by different operating systems and/or software versions and the same holds for partial dates such as year only. It may be advisable to also enter dates before that year in the Circa Date Created field. Do not confuse this field value with the Date Created field for the image showing this artwork or object.
* **Circa Date Created (AO)**\
A free text field for use where the exact date of creation of the artwork or object is unknown. An approximate date is entered in text rather than date format e.g. ‘ca 1900’, ‘19th century’
* **Style Period (AO)**\
Free-text field for style, historical or artistic period, movement, group, or school describing  the artwork or object.
* **Creator (AO)**\
Name of the creator of the artwork or other objects in the image. Where the artist cannot or should not be identified, the name of a company or organisation may be used. Do not confuse this field value with the Creator of the image showing this artwork or object.
* **Creator ID (AO)**\
Globally unique identifier for the creator of the artwork or object in the image. For example use an identifier issued by an online registry of persons or companies.
Multiple IDs should be entered in the same sequence as the creator names.
Do not confuse this field value with the Creator Id of the Image Creator of the image showing this artwork or object.
* **Source (AO)**\
Name of the organisation or body that holds or has registered the artwork or object for inventory purposes.
* **Source Inventory Number (AO)**\
Inventory number issued by the Source, for example an accession number.
* **Source Inventory URL (AO)**\
URL supplied by the Source for the online metadata record.
* **Copyright Notice (AO)**\
Copyright notice for claiming the intellectual property for the artwork or object in the image. It should identify the current owner of the copyright and associated intellectual property rights.
Do not confuse this field value with the Copyright Notice of the image showing this artwork or object.
* **Current Copyright Owner Name (AO)**\
Name of the current owner of the copyright in the artwork or object.
Do not confuse this field value with the Name field of the Copyright Owner of the image showing this artwork or object.
* **Current Copyright Owner ID (AO)**\
A globally unique identifier for the current copyright owner e.g. issued by an online registry of persons or companies.
Do not confuse this field value with the Identifier field of the Copyright Owner of the image showing this artwork or object.
* **Current Licensor Name (AO)**\
Name of the current licensor of the artwork or object.
Do not confuse this field value with the Name field of the Licensor of the image showing this artwork or object.
* **Current Licensor ID (AO)**\
A globally unique identifier for the current licensor e.g. issued by an online registry of persons or companies.
Do not confuse this field value with the Identifier field of the Licensor of the image showing this artwork or object.

