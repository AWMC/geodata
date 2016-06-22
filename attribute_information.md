# AWMC Attribute Information
 This file lists the attributes used in AWMC geodata

Attribute Name | Data Type | Description
-------------- | --------- | -----------
awmc_class | Integer | An optional attribute which may not be appropriate for all data types. The “ranking” of the importance of the feature. This is a choice of 1 – 4. A rough guide follows: 1) In all BGLT maps 2) Named in Barrington Atlas 3) In Barrington but unnamed 4) Not included in the Barrington due to lack of notoriety / scale.
contributor | Text | The GitHub ID of the contributor who created / modified the initial resource.
description | Text | This is the description of the resource, where a user can provide more detail than the type.
notes | Text | Any notes about the feature (uncertainty, etc) that are useful for the center
pleiadesid | Text | The Pleiades URI that corresponds to the feature (if available). 
timeperiod | Text | Time Period URI from http://perio.do/
title | Text | The English language description of an item. This can be a road tittle, a place name, etc. This information can be automatically pulled from Pleiades, but it is included in our files to aid in map creation.
type | Text | The type of the resource that corresponds to Pleiades types. As types are currently under discussion at Pleiades, this will almost certainly change to a URI that points to Getty vocabularies or some other resource.
initial_provenance | Text | URI to the original source of the information. This can be a worldcat item, a Zotero library entry, or some other URI.
citations | Text | URIs, separated by a semi-colin, which point to further infromation or controversies over the feature. 
