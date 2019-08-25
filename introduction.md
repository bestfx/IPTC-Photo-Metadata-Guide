## Introduction
This document is designed to familiarise photographers, photo editors and metadata managers with the use of the IPTC Photo Metadata Standard. It provides a short guideline on the use and semantics of each IPTC field (also called metadata property).

The User Guide groups fields according to their category of use:

* General image content
* Person(s) shown in the image
* Locations relevant to the image
* Other things shown in the image, including artwork
* How to assert rights and license usage
* Administration and Commissioning details

The [Field Reference table][sms] lists all IPTC fields with their field labels for easy reference. 

[sms]: https://www.iptc.org/std/photometadata/documentation/userguide/Documents/fieldreferencetable.htm

The [What Is A …][sms] section explains terms used by the IPTC Standards.

[sms]: https://www.iptc.org/std/photometadata/documentation/userguide/Documents/whatisahelp.htm

There is a [help section on specific topics][sms] such as mapping Category Codes to Subject Codes.

[sms]: https://www.iptc.org/std/photometadata/documentation/userguide/Documents/helponspecifictopics.htm

Sample images are shown with [full examples of metadata][sms] to aid in practical metadata entry.

[sms]: https://www.iptc.org/std/photometadata/documentation/userguide/Documents/howtousemetadataexamples.htm

More [about this User Guide][sms], including how to contact IPTC and a Copyright Notice, is also available.

[sms]: https://www.iptc.org/std/photometadata/documentation/userguide/Documents/abouttheiptcphotometadatauserguide.htm

## Purpose of IPTC Photo Metadata

Photo metadata is key to protecting images' copyright and licensing information online. It is also essential for managing digital assets. Detailed and accurate descriptions about images ensure they can be easily and efficiently retrieved via search, by users or machine-readable code. This results in smoother workflow within organizations, more precise tracking of images, and increased licensing opportunities.

Therefore, photo metadata is critical to photo and related business. IPTC has specified metadata to meet these needs; it is the industry standard of professional photography.

## The Evolution of IPTC Photo Metadata

The IPTC - www.iptc.org - is a body of content providers and system vendors from the news industry and has defined standards for metadata about news since 1979. Since the mid 1990’s IPTC metadata are have been quite popular for photos as they were adopted by Adobe Photoshop at this time. The IPTC Photo Metadata Standard defining the Core and Extension metadata schemas is the second generation of IPTC photo metadata.

IPTC’s older standard for metadata, the Information Interchange Model (IIM), was issued in 1991 and defined a set of metadata properties and a data format to embed the metadata values into image files. In the early nineties a subset of this IIM was adopted as the well-known “IPTC Fields by Adobe Photoshop and can be embedded into JPEG, TIFF and PSD files since then.

In the early 2000-years a new technology for embedding metadata into image files was invented. It is called XMP, was developed by Adobe and is now an ISO standard. This technology required defining new technical specifications for the well-known “IPTC Fields” of the IIM standard and this was done by the IPTC Core schema which was initially released in 2005 and has evolved to version 1.2 since then. A key feature in the transition to IPTC Core in XMP was that the definition of the purpose and the specified use of an IIM field should remain the same, with only the underlying technical details changed. As the IPTC Core is in fact a mirror of the IIM fields it will no longer be extended.

Discussion of IPTC Core raised the need for additional metadata properties not covered by the IIM standard. IPTC created the IPTC Extension schema in 2008. IPTC Extension has been updated twice and is since November 2014 at version 1.2. Any future additions to the IPTC Photo Metadata will be part of the IPTC Extension schema.

After development over two decades IPTC Photo Metadata can be embedded in the following ways:

* IPTC Core fields can be embedded in the IIM format and/or in the XMP format. A key challenge for metadata embedded in parallel in IIM and XMP is that the values are synchronised – this should be taken care of by the image management software.

* IPTC Extension fields can be embedded only in XMP format.

To help users, the IPTC collects information from software vendors on their support for IPTC Photo Metadata. Find out more at www.iptc.org/photometadata.

Be aware that IPTC Core and IPTC Extension fields can be saved as XMP “sidecar files” for camera Raw files and those file formats which do not support embedded metadata.
