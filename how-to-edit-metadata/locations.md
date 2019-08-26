## Locations
The original ‘Location’ fields in IPTC (Core) do not distinguish between the location where the image was created and the location shown in the image. The IPTC Location Created and Location Shown field structures were added later to remove this ambiguity.

When populating the Location fields, it is good practice to start with the sublocation which is at the lowest level of the location hierarchy. The wider Location terms define the position of the sublocation.

> Read also about metadata for specific content on pages about [general image content](https://www.iptc.org/std/photometadata/documentation/userguide/Documents/generalimagecontent.htm), [persons](https://www.iptc.org/std/photometadata/documentation/userguide/Documents/personsdepictedintheimage.htm or [other things](https://www.iptc.org/std/photometadata/documentation/userguide/Documents/otherthingsshownintheimage.htm (organisations, events, products, artwork, objects).

All location [field structures](https://www.iptc.org/std/photometadata/documentation/userguide/Documents/whatisahelp.htm use the following geographic hierarchy:

#### Sublocation
This could be the name of a specific area within a city (Manhattan) or the name of a well-known location (Pyramids of Giza) or a monument or natural feature outside a city (Grand Canyon, Mont Blanc Peak):

The area covered by Sublocation may differ for the two types of location. For Location Created, the sublocation might be derived from the Exif GPS coordinates of the camera. In general, the Location Shown should specify the area of interest shown in the image, which is a broader area e.g. The Vosges Mountains.

| Item | Description |
|----|----|
| *City*: | The name of the city or town or nearest human settlement such as village.  If there is no data for ‘city’, leave the field blank and enter details in sublocation and other fields in the hierarchy. |
| *State/Province*: | The name of the State or Province or other sub-region of a country. Use of the full name, rather than the abbreviation, is advisable for international audiences. 
| *Country*: | The name of the country.
| *Country Code*: | Country codes are two or three letter upper-case codes as defined by the ISO 3166 standard. The codes are available from: https://www.iso.org/obp/ui/. If both the Country and Country Code fields are used, the Country Code is the authoritative reference. Most photo businesses use the 3 letter code.
| *World Region*: | The name of the region of the world. |

> BE AWARE: the location fields are limited by the IIM format to about 32 characters. In XMP there is effectively no character limit.

### Location (Original/Legacy)
The legacy Location fields – in most cases shown as sequence of stand-alone fields - are widely understood to express the location shown in the image. They can be used where it is important to display the location values in software which does not read Location Created and Location Shown field structures. Some software applications copy data from the Location fields to the field structure ‘Location Shown.’

| Item | Description |
|----|----|
| *Location Created* | is the location where the image was created. Use this field structure to specifically record the location where the photo was taken. If the location shown in the image is different from the location where the photo was taken then the IPTC field structure ‘Location Shown in the Image’ should be used to note the difference. For example, if you are photographing a mountain with a telephoto lens from a distance, you may be standing on the other side of a state or even country border.
| *Location Shown in Image* | This field structure describes the location shown in the image. Where the subject of the image is in a different location to the camera the values should differ from those in ‘Location Created’. |
