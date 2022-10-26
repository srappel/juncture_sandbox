<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Milwaukee Annexation"
       author="Stephen Appel"
       banner="https://uwm.edu/wp-content/uploads/sites/59/2014/07/agsl_page_header.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

This is a sample visual essay to demonstrate how to use Juncture to build visual essays. The banner image features one of NASA's images from the Hubble Telescope, showing a small region of space in the constellation Fornax [^1]. To the right, the first image in the essay is a much earlier rendition of a more nearby celestial phenomenon, the movement of the planets. This is from the UWM Libraries American Geographical Society Library digital collection featuring the Atlas Novus Coelestis, from 1742. 
<param ve-image fit="contain"
       manifest="https://collections.lib.uwm.edu/iiif/info/agdm/25606/manifest.json">  
  
## IIIF image "to fit"

Here is the same image using the fit="contain" instructions. Simple but very useful. 
<param ve-image fit="contain"
       manifest="https://collections.lib.uwm.edu/iiif/info/agdm/25606/manifest.json">

## Image without zoom

Globi Coelestis in Tabulis Tlanas Redacti Pars I: Full size with no zoom or fit="contain" code. 
<param ve-image  
       manifest="https://collections.lib.uwm.edu/iiif/info/celestial/84/manifest.json">
    
## Image with zoom

Globi Coelestis in Tabulis Tlanas Redacti Pars I0: Zoomed in using image coordinates to focus on a particular part of the image (in this case, an image of the "camelopardalus" constellation).
<param ve-image region="2324,2293,1305,1083"
       manifest="https://collections.lib.uwm.edu/iiif/info/celestial/84/manifest.json">
      
## Image with zoom-to

In this image, you can also see part of the constellation <span data-click-image-zoomto="2952,644,1812,1504">Cygnus</span>. You can also zoom in closer to view details of the image for constellation <span data-click-image-zoomto="3089,1412,1258,1045">Cephus</span>. 
<param ve-image  
       manifest="https://collections.lib.uwm.edu/iiif/info/celestial/84/manifest.json">    
     
## Map image

You can use Juncture to great effect with images of maps. This is a nautical chart of South Orkney, dated 1847. It's very sparse, but you can zoom in to better view <span data-click-image-zoomto="8121,1033,2023,1646">Georgie du Sud and the Cape of Disappointement</span>. You can also veer south to better view <span data-click-image-zoomto="4916,5733,2023,1646">Coronation Island</span>. 
<param ve-image  
       manifest="https://collections.lib.uwm.edu/iiif/info/agdm/21500/manifest.json">

## Map

The South Orkney Islands are a group of islands in the South Atlantic Ocean. We are using the map information from Wikidata to create the map to right.
<param ve-map center="Q207383" zoom="11">

Lat/long based map - using decimal-based lat/long for Buenos Aires in Argentina - north of the South Orkney Islands but nearby, relatively speaking.
<param ve-map center="-34.368, -57.596" zoom="9">

## Video

You can also include Youtube videos by using the param ve-video code and the youtube video ID. This is an official NASA video with highlights from the first images to be sent back from the James Webb Space Telescope, from July 2022.
<param ve-video id="1C_zuHf6lP4" title="Highlights: First Images from the James Webb Space Telescope (Official NASA Video)">

## Finding IIIF resources

This image is a page from a fourteenth century copy of Al-Sufi's "Book of the Constellations of the Fixed Stars," held by the National Library of France, and featured in the Library of Congress's [World Digital Library](https://www.loc.gov/collections/world-digital-library/about-this-collection/) collection. [*Al-Sufi's "Book of the Constellations of the Fixed Stars," followed by Maxims, and al-Qazwini's "The Wonders of Creation".*](https://lccn.loc.gov/2021667391)
<param ve-image 
       manifest="https://www.loc.gov/item/2021667391/manifest.json">       
  
  
# References

[^1]: Image: NASA and the European Space Agency., Public domain, via Wikimedia Commons" [href="https://commons.wikimedia.org/wiki/File:Hubble_ultra_deep_field.jpg](https://commons.wikimedia.org/wiki/File:Hubble_ultra_deep_field.jpg)
