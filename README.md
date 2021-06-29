# Predicting burrowing crab impacts on salt marsh plants
This is the collective data for Dr. Jan Walker's work on the effect of burrowing crabs on the salt marsh plant community in California.

The repository includes data used in the analyses for - 

    Walker, J.B., S.A. Rinehart, W.K. White, E.D. Grosholz, and J.D. Long. 2020. Local and regional variation in effects of burrowing crabs on plant community structure. Ecology 102(2):e03244. DOI: 10.1002/ecy.3244
  
    Walker, J.B., E.D. Grosholz, and J.D. Long. 2021. Predicting burrowing crab impacts on salt marsh plants. In press, Ecosphere.
  
    Walker, J.B., University of California, Davis. ProQuest Dissertations Publishing, 2020. 28092194. https://www.proquest.com/openview/acafe91f39d311411fad803988613859/1?pq-origsite=gscholar&cbl=44156

The first group of data files include data collected from 2016 to 2019 at six sites - 
  1) KF1 - Kendall-Frost 1
  2) KF2 - Kendall-Frost 2
  3) SDL - San Dieguito Lagoon
  4) BOL - Bolinas Lagoon
  5) TOM - Tomales Bay
  6) BOD - Bodega Bay

All data files note the Year, Month, Day, Marsh, Zone, Cage, and Treatment - 
  1) Year - 2016, 2017, 2018, 2019
  2) Month - January - December
  3) Day - 1-31
  4) Marsh - KF1, KF2, SDL, BOL, TOM, BOD
  5) Zone - reg, hi, lo, mid [only zones reg and mid were used in the above publications]
  6) Cage - replicate number
  7) Treatment - no (no crabs), ambient (ambient levels of crabs), high (high crab densities), ncc (no-cage controls), cc (cage-controls)

8 files include the data collected in the manipulation of burrowing crabs from 2016 to 2019 in the above publications.

1) Cage_Burrows_Data_NS - Burrows: Total number of burrows counted in each plot; Pachy, Hemi, Fiddler, Green: The number of crabs sighted for each species in each plot; Pitfall: Total number of crabs caught in the pitfall traps; Pitfall-F, Pitfall-P, Pitfall-G, Pitfall-H: The number of crabs caught in pitfall traps for each species
2) Cage_CrabDiameter_all_NS - diameter: The burrow diameter measured in cm
3) CageData_all_NS - Stems(all): total cordgrass stem number; Stems(live): live cordgrass stems; Stems(dead): dead cordgrass stems; Flowers: total number of flowering cordgrass stems; Pickle_CH_Avg: Average pickleweed canopy height in cm; Spartina_L: live cordgrass percent cover; Spartina_D: dead cordgrass percent cover; Mud: percent cover of mud; Sarcocornia: pernennial pickleweed (Sarcocornia pacifica) percent cover; Salicornia: annual pickleweed (Salicornia bigelovii) percent cover; Batis: Batis maritima percent cover; Jaumea: Jaumea carnosa percent cover; Triglochin: Triglochin maritima percent cover; Unknown: unknown plant percent cover; Wrack: percent cover of wrack (kelp, eelgrass, etc.); Not_visilble: percent cover of areas that weren't visible due to water
4) Cage_CordgrassHeight_all_NS - CordgrassHeight: The height of Spartina foliosa (cordgrass) in cm
5) Cage_AbovegroundBiomass_all_NS - Plant: Ba (Batis), CD (Cordgrass Dead), CL (Cordgrass live), Pi (pickleweed - Sarcocornia pacifica), other (all other plants); Mass.Final: the mass in g of each dried plant
6) Cage_BelowgroundBiomass_all_NS - Plant: Cordgrass, Pickleweed (Sarcoconia pacifica), Other; Final.Mass: the mass in g of each dried plant
7) Cage_Porewater_NS - The porewater measurments for Nitrate (um/L), Ammonium (um/L), Salinity (ppt), UV (Dissolved organic carbon recording aborbance at A260 nm)
8) Cage_CtoN_NS - Plant: Cordgrass, Pickleweed (Sarcocornia pacifica); TotalC.ug: amount of carbon; TotalN.ug: amount of nitrogen; ratio: Carbon to nitrogen ratio

The second group of data files are the data collected from the feeding assays described in Walker et al. 2021.

1) FeedingAssays_Site_2018 - Year: 2018; Month: June-July; Region: North or South; Site: BOD, TOM, BOL, SDL, KF2, KF1; Trial: 1-6; Replicate_og: the number written on the container in the assay; Replicate: The replicate number given based on site; Species: CR (cordgrass roots), CL (cordgrass leaves), PR (pickleweed roots), PL (pickleweed leaves); Plant: Cordgrass or Pickleweed; Consumption: Total consumption throughout the assay calculated with formulas in Walker et al. 2021; Time: The total time the assay was performed for each replicate
2) FeedingAssays_Site_2018_crab_g - Crab: the weight of the crab in g
  
 For further information, please reach out to Jan Walker - janw@sccwrp.org 

