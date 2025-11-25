This README explains the format of the datasets deadorgone and alldata_full, most of which are identical. 

The description of each column is as follows:

Species - The 4-letter code desribing the taxonomic identity of each species. Where species identification was not possible, some groups of species were aggregated into morphotaxa, which are as follows:

Atab : Tabular Acopora
Poci : Branching Pocillopora (damicornis and verrucosa)
Adgt : Acropora digitate
Spis : Stylophora pistillata
Pmas : Porites massive
Gspp : Goniastrea spp (submassive)
Plat : Platygyra spp (submassive)
Acor : Corymbose Acropora

temp_mean - Average daily temperature (degrees celcius) over the period, derived from eReefs
ubedmean - Near bet water velocity (m/s) based on the Callaghan wave model, in 15x15m grid cells, extracted over the sampling period from 2021-2022
Turbidity_mean - Nephelometric Turbidity Units, expressed as daily average estimates from the period 1 Jan 2015 to 1 Jan 2021
rugosity - Plot level rugosity of 3D models of each plot, relative to a plane of best fit
Depth - Shallow (3-5m) or Deep (13-15m) depth category
Plot_ID - Unique identifier for each individual 12x6m plot
Area_2022 - 2D planar colony area in 2022 in square cm
Area_2021 - 2D planar colony area in 2021 in square cm
return_months - return time (to the nearest month)
shelf_position - denotes whether the plot was inshore, offshore, or in the Torres Strait
habitat - categorical variable. Front = Exposed, Back = sheltered, flank = moderately exposed to prevailing wave direction
region - Latidute of sites, either Central, Northern, Southern or Torres Strait
reef - Reef name
FD_Rugosity_Plane - Fractal dimension of rugosity, adjusted to the plane of best fit for each 3D model of the 12x6m plot
PAR_mean - Photosynthetically active ratiation, expressed as PAR; mol photon m-2 s-1 averaged over the period 1 Jan 2015 to 1 Jan 2021
site - Unique classifier for each individual 12x6m plot
hard_coral_21 - Plot level hard coral coverage in 2021 (first year of sampling)
mothlygrowth - Monthly 2D planar growth rate in square centimeters (not used in any analyses)
yearlygrowth - Annualised 2D planar growth rate in square centimeters (not used in any analyses)
area_2022_adjusted - Adjusted area in 2022 to account for differences in return time for each reef
log22 - log-transformed (base e) of 2D colony area (square centimeters) in year 1
log21 - log-transformed (base e) of 2D colony area (square centimeters) in year 2
log22_adj - log-transformed (base e) of 2D colony area (square centimeters) in year 2 adjusted to account for differences in return time for each reef

Important: EcoRRAP abbreviations for habitat types and cluster / reef names

EcoRRAP Abbreviations

Clusters:
 - CB: Capricorn Bunkers
 - KE: Keppel Islands
 - OC: Offshore Central
 - PA: Palm Islands
 - ON: Offshore Northern
 - TS: Torres Strait

Reefs: 
 - LM: Lady Musgrave
 - HE: Heron Island
 - HW: Halfway Island (Keppel Island group)
 - GK: Greak Keppel Island
 - MD: Middle Island (Keppel Island group)
 - ML: Miall Island (Keppel Island group)
 - NK: North Keppel Island
 - DA: Davies Reef
 - LB: Little Broadhurst Reef
 - CH: Chicken Reef
 - OR: Orpheus Island
 - PE: Pelorus Island
 - MO: Moore Reef
 - LI: Lizard Island
 - AU: Aukane Island
 - DU: Dungeness Reef
 - MA: Masig Island

Habitats (numbers associated with habitat abbreviation indicate multiple sites of a habitat type within a reef, e.g. BA1 is 'back 1' while BA2 is 'back 2'):
 - BA: back
 - FL: flank
 - FR: front
 - LA: lagoon

 - Thus, CBLM_FR1 would be Cluster: Capricorn Bunkers, Reef: Lady Musgrave, Habitat: Front, Plot: 1
