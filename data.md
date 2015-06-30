---
layout: default
title: Data
permalink: /Data/
---
### The Data
<figure class="figure figure-center">
<img src="http://i.imgur.com/GlM9NLd.jpg"  title="Knoedler Dataset">
<figcaption>Clean data set of the first six stock books from the Knoedler Gallery Archive, exported from the Getty Provenance Index database. <a href= "https://drive.google.com/open?id=0BxxB10Erjo-Ua1NRUWtVOGdhbzlWT2JkQWJPMFJTdjlqSGNR&authuser=0">Click here</a> to use this data.</figcaption>
</figure>



As described in the History section of our website, this dataset is the result of countless hours transcribing handwritten stock books. There are multiple levels of human interaction with the data that results in no small number of idiosyncrasies and inconsistencies. This is a simple reality of working with structured data and it proves to be a major challenge when working with visualization software that can only be successful when the data is consistent.

### Challenges: Location

One particular challenge we came across is determining location names. Over the course of the thousands of entries one can find references to English, French, and vernacular or local-language names for the same city. Diacritics are not universally applied, so that searches for the accurate vernacular München (Munich) will miss the countless Munchen entries.

A similar difficulty emerges on a more domestic level for art objects that were sold in the New York metropolitan area. Each borough, even post-incorporation, may be referred to as a discrete locality, often designated by baffling shorthand (Broo.lyn, Brk.lyn, etc). Furthermore, sales within Manhattan are designated by 'City' or simply a street address. The latter in particular thwarts many of the tools available to data cleaners because the powerful 'find/replace' and 'filter' functions are rendered useless. In the version that is available for download, the major city names have been standardized but the Manhattan locations, much like their real-life counterparts, remain chaotic and unusable. Finally, even when these location fields are standardized most mapping visualization tools can only use coordinate data and, as a result, there is an additional labor of converting the text locations to numeric coordinates.

The date format provided a significant challenge which, much like location names, develops at multiple stages in the process. Although the transcribers do an excellent job of standardizing date information to a mm/dd/yyyy format, the authors of the stock book occasionally abbreviate dates to a simple mm/yyyy format, consigning the exact day to obscurity. In these cases, we have simply used the first day of the month as a place holder (see Data Provenance section below). The next challenge is the way Microsoft Excel and/or Google Docs understands dates and their formatting. In the first place, dates before 1900 can only be treated as raw information, preventing Excel from sorting those dates appropriately. That wouldn't be so bad if one could simply convert all date information to the mm/dd/yyyy format and then treat all date values as raw information so that entries could be sorted chronologically. Instead, Excel employs a bewildering system wherein readable date values (1900 and on) are converted to a nonsensical five digit number when represented as raw information and not 'Date' formatted. The most successful but not entirely satisfying solution we found is detailed in the Data Provenance document.

<a href="http://www.getty.edu/research/tools/vocabularies/tgn/">The Getty Thesaurus of Geographic Names</a> proved an invaluable reference during this phase of data cleaning. Not only does it offer an authoritative name for locations,but geographic coordinates are also included within each entry.

These two examples highlight the complexity of operation required to get the data into shape for use in the visualization tools. They also illustrate the many moments in which a researcher alters the data they’ve received. As this alteration is a necessary evil, it is essential that these changes are tracked and detailed, if not only to lend credibility to any results the researcher might publish or present but also for the researcher’s own records (and sanity).

### Challenges: Date

The date format also provides a significant challenge. Much like location names, the data develops at multiple stages in the process. Although the transcribers do an excellent job of standardizing date information to a mm/dd/yyyy format, the authors of the stock book occasionally abbreviate dates to a simple mm/yyyy format, consigning the exact day to obscurity. In these cases, we have simply used the first day of the month as a place-holder (see our Data Provenance document for further information).

The next challenge is the way Microsoft Excel and Google Docs understand dates and their formatting. In the first place, dates before 1900 can only be treated as raw information, preventing Excel from sorting those dates appropriately. That wouldn't be so bad if one could simply convert all date information to the mm/dd/yyyy format and then treat all date values as raw information so that entries could be sorted chronologically. Instead, Excel employs a bewildering system wherein readable date values (1900 and on) are converted to a nonsensical five-digit number when represented as raw information and not 'Date' formatted. The most successful but not entirely satisfying solution we found is detailed in the Data Provenance document. 

These two examples (location and date format) exemplify the complexity of operation required to get the data into shape for use in the visualization tools. They also illustrate the many moments in which a researcher alters the data they’ve received. As this alteration is a necessary evil, it is essential that these changes are tracked and detailed, if not only to lend credibility to any results the researcher might publish or present but also for the researcher’s own records (and sanity). 

### Data Provenance

By definition data provenance is the tracking of changes made in the cleaning of data sets. <a href= "https://drive.google.com/open?id=0BxxB10Erjo-UbmtQcnNNUDR0REdYY3FHLXhBQ0lMX0ZkRDBn&authuser=0">Click here</a> to view our document. For more information about Data Provenance please refer to our resource page.



