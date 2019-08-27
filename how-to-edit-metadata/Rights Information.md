## Rights Information
This section is about how to record rights information for an image.

> Read also the page about [licensing the use of the image].

The creator of the image has owner of rights that can be identified by two properties
* **Creator**, a free text field for the name of the Creator
* **Image Creator**, a field structure including the name of the Creator and an identifier for the Creator  

IPTC recommends using the older Creator name only field for all images. The newer field structure (Name and ID) should be used in addition to this, when a Creator identifier is available.  

Creator data saved in these fields should not be altered over time.

The Image Creator, Copyright Owner, Image Supplier and Licensor may be the same or different entities.

#### Creator (free text)
Name of the creator of the image. Where the artist cannot or should not be identified, the name of a company or organisation may be use.
> <ins>BE AWARE</ins>: this field is limited by the IIM format to about 32 characters. In XMP there is effectively no character limit.
> <ins>BE AWARE</ins>: this field is shown in the Image Credits of a photo in the results of a Google image search.

#### Image Creator (structure)
This property can be used to indicate the creator or creators of the image by name and identifier.

#### Creator’s Job Title
The job title of the person who created the photograph. For examples this might include titles such as: Staff Photographer, Independent Commercial Photographer, or staff writer. Since this is a qualifier for the Creator field, the Creator field must also be filled out.
> <ins>BE AWARE</ins>: this field is limited by the IIM format to about 32 characters. In XMP there is effectively no character limit.

#### Creator’s Contact Info
The Contact Info fields provide a generic structure for storing contact information for the person or organisation that created this image.
* **Address (CCI)** \
The address field is a multi-line field. Enter the street name and number or postbox to which mail should be sent, and a company name or location (building name, floor number) if necessary. 
* **City (CCI)** \
The name of the city in which the primary contact’s business is located.
* **State/ Province (CCI)** \
The State or Province in which the primary contact’s business is located. For clarity, it is best to use the full name rather than the abbreviation.
* **Postal Code (CCI)** \
The local postal code (such as ZIP code) in which the primary contact’s business is located.
* **Country (CCI)** \
The name of the country (or ISO Country Code) in which the primary contact’s business is located.
* **Phone(s) (CCI)** \
The primary contact’s business or work telephone number. Multiple numbers can be given, separated by a comma.  Be sure to include the complete international format of a phone number which is: +{countrycode} ({regional code}) {phone number} - {extension if required}
e.g. +1 (212) 1234578
* **Email(s) (CCI)** \
The primary contact’s business or work email address, such as name@domain.com. Multiple email addresses can be given, separated by a comma.
* **Website(s) (CCI)** \
The URL or web address for the primary contact’s business. Multiple addresses can be given, separated by a comma.

#### Copyright Notice
The Copyright Notice contains information required to assert copyright in the image and should contain the name of the current copyright holder, whether an individual or a company. The format will differ according to the relevant copyright legislation. It may include the copyright symbol ©, the year of publication, and other commonly used terms such as ‘All Rights Reserved.’ If an image is Public Domain, it can be indicated here.

For legal advice on asserting copyright, you should consult a lawyer.

Notes on usage rights (how the image may be used) should be provided in the “Rights Usage Terms” field.

> <ins>BE AWARE</ins>: this field is limited by the IIM format to about 128 characters. In XMP there is effectively no character limit. \
> <ins>BE AWARE</ins>: this field is shown in the Image Credits of a photo in the results of a Google image search.

#### Copyright Owner
Indicate the owner or owners of the copyright in the image, using name and identifier. Note that Copyright Owner, Image Creator, Image Source and Licensor may be the same or different entities.

#### Credit Line
The Credit Line shows how the image should be credited when published, as specified by the supplier of the image. The format varies for different suppliers and may contain: Agency Name, Photographer Name, Rights assertions. E.g. Agency/Photographer; © Photographer; Museum/Artist

The Credit Line may contain information also listed in other fields such as Creator, Copyright Notice, Supplier.

> **NOTE**: In IPTC Core version 1.0 this field was named ‘Provider’ \
> <ins>BE AWARE</ins>: this field is limited by the IIM format to about 32 characters. In XMP there is effectively no character limit. \
> <ins>BE AWARE</ins>: this field is shown in the Image Credits of a photo in the results of a Google image search.

#### Source
The Source field is used to name parties with a role in the supply chain, such as agencies, originating organisations, or photographers. The Source field is useful for syndication where the original supplier agency or photographer  is different from the end supplier.

> **NOTE**: before the IPTC Photo Metadata Standard 2014 the semantics of this field were restricted to the original copyright owner of the image.) \
> <ins>BE AWARE</ins>: this field is limited by the IIM format to about 32 characters. In XMP there is effectively no character limit.

#### Property Release Status
This field summarises the availability and scope of property releases for the photograph. There are four possible values:
* None (no release is available)
* Not Applicable (there are no items requiring a property release in the image)
* Unlimited Property Releases (releases are available for all property shown in the image)
* Limited or Incomplete Property Releases (there are releases for some property shown in the image).

We recommend that the PLUS specified value Unlimited Property Releases (PR-UPR) be used with care, and encourage you to check the wording of the property release thoroughly before choosing this value.

#### Property Release Identifier(s)
Use this field to indicate the ID for each Property Release document. Ensure all releases (both model and property) are assigned a unique number, and record that information in this field.

> Read about Model Releases on the page about persons in an image.

#### Web Statement of Rights
The Web Statement of Rights can be used to link the viewer to a web page (by a URL) which provides a statement of the copyright ownership and usage rights of the image. In the Adobe ‘File Info’ panel this field is called the ‘Copyright Info URL.’

