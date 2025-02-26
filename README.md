ESA Listed Vs NonListed Publication Counts

Abstract
The Endangered Species Act (ESA) of 1973 uses the best available science to protect threatened and endangered species, but limited knowledge of listed species can undermine conservation success. This study examined whether ESA-listed species receive more peer-reviewed publications than ecologically and geographically similar non-listed species. We randomly selected 50 ESA-listed species across five taxonomic groups (birds, fish, herpetofauna, invertebrates, and mammals), pairing each with a comparable non-listed species, and compared annual peer-reviewed publication counts. We used generalized linear mixed models to evaluate the effects of taxonomic group and year on publication differences. Results showed an increasing bias in research effort favoring non-listed species, including greater attention to charismatic species or those with dedicated funding. This research disparity raises concerns, as peer-reviewed studies are vital for policy decisions. Increased funding and targeted research on under-studied ESA-listed species are critical for informed conservation strategies and improved ecological outcomes.

Description of the data and file structure
Data were collected using literature searches in Scopus. Using the “Article title, Abstract, Keywords” search field, we entered the species’ common and scientific names in quotes, separated by “OR” (e.g., “piping plover” OR “Charadrius melodus”). For species with multiple common names, all variants were included in an “OR” statement alongside the scientific name (e.g., “Bolson tortoise” OR “Mexican gopher tortoise” OR “Gopherus flavomarginatus”). If a common name contained an apostrophe, we included both the apostrophized and non-apostrophized versions (e.g., Kirtland’s warbler” OR “Kirtlands warbler” OR “Dendroica kirtlandii”). We recorded the publication year and the corresponding number of peer-reviewed literature associated with each species and taxonomic group. To evaluate whether peer-reviewed publication counts were biased toward listed or non-listed species, we calculated the annual difference in peer-reviewed publications for each species pair by subtracting the count of the listed species from the count of the non-listed species. Differences near zero indicated minimal disparity in research effort between species, while larger deviations suggested a greater bias towards one species.

File: ESA_pubs_source.csv
Description:  Discrepancy in the number of publications between paired listed and non-listed species 

Variables
PairNames: Common names of the focal species that include L for listed and NL for not listed.
ListedYear: The year the listed species was listed.
PublicationYear: The publication year.
Group: The taxonomic group
PubDiff: The difference between the number of publications between the listed and non-listed species.
