# M.Sc. Inventories and Applied Geomatics
## General Course Information

https://campus.uni-freiburg.de:443/qisserver/pages/startFlow.xhtml?_flowId=detailView-flow&unitId=126509&periodId=2483&navigationPosition=examEventOverviewOwn

Start 17.10.24

Thursday 13-17 Uhr in Herderbau (R 400, 4th floor)

**Exam date: 13.02.2025, 13-17 PM, R400**

## Preliminary Agenda:

1. Introduction to the module
2. Theory of forest inventories
3. GNSS position determination                          (Field exercise)
4. Mooswald inventory field exercise                    (Field exercise)
5. Sampling uncertainties
6. Allometries
7. Introduction to drone remote sensing                 (Field exercise)
8. LIDAR data
9. Introduction to AI inventory
10. AI inventory (Part 2)
11. deadtrees.earth
12. deadtrees.earth (Part 2)
13. Introduction to large-scale forest information products
14. Summary and exam review

---------------------------

# News

## 12.12.24
- **Lecture: Introduction to AI in Inventory**
    - Individual tree detection
    - Species recognition
    - Tree height
    - Trunks vs. branches vs. leaves, etc.

- **Exercise: Applying AI to LIDAR Data / Evaluation - Part 1**
    - UAV data: Tree positions, tree heights (part 1)
    - Comparison with full inventory from ECOSENSE (part 2 next week)
        - DBH, stand density
        - Comparison of plot-based inventory vs. AI/drone-based inventory

## 05.12.2024

(08_droneslidar)

- Inventory by drone
- Introduction to LiDAR data processing
- Introduction to AgiSoft Metashape (brief)
- Presentation of geodata products
- Introduction to the lidR package

## 28.11.2024 (Field day)

(07_satelliteimagery)

**Please wear sturdy footwear and warm clothing!**

- 13:30-17:00 +-
- Meeting point punctually(!!!) at Vogelsanghütte (near Ebnet):

https://maps.app.goo.gl/tZVoGPWRAtX9x6Vx5

**By bike, it takes about 20 minutes from Herderbau, by public transport + walking about 45 minutes**

### Field Day! (Max, Teja)

- Introduction to remote sensing data
- Platforms: Drones, airplanes, satellites, advantages, disadvantages
- Sensors: Advantages, disadvantages
- Geodata products (vector, raster)
- Demonstration of drones + TLS
- Stations for thermal, LiDAR, multispectral

------------------------------

## 21.11.2024

(06_allometries)

### Lecture (Thomas S.): Allometries

- Introduction and history
- Estimation of wood stock, biomass, modeling, predictions, etc.
- Influencing factors on allometries (stand density, management, site factors, etc.)
- From DBH → biomass/wood stock (needed for exercises)

### Exercise: Allometries and wood stock in R (Max, Teja)

- Apply allometries to full inventory ECOSENSE based on the R scripts from the previous week
- Evaluate and discuss the impact of sampling uncertainties on allometries

--------------------------

## 14.11.24

(05_uncertainties)

- Please bring your laptops and have RStudio installed!

### Lecture and Exercise (Max):

- Review of the inventory
- Comparison of inventory metrics per plot of different groups
- Introduction to sampling uncertainty
- Introduction to full inventory data Ettenheim
- Introduction to R script for sampling

## 07.11.2024 (Field Day)

folder: 04_accuracy_inventory

### Field Day (Max, Teja, Jon): 13:00-17:00 +-

- Debriefing field exercise on position determination
- Discussion on GPS inaccuracy (approx. 15 minutes)
- Collecting / experiences / discussion
- Preliminary discussion on Mooswald inventory (1 hour)
- Jon Sheppard takes over (some may know him from previous semesters)
- Briefing on procedures and tasks
- Field exercise inventory in Mooswald (species, DBH, position, etc.)
- Bring food
- Measure each plot 2-3 times
- Wear sturdy footwear, etc.
- Formation of several student groups
- Groups switch to the next plot after inventorying the current plot, so that multiple inventories per plot are available for comparison in the debriefing (e.g., n=3 with 3 runs). For example, with 8 groups, there are 8 plots. Group 1 starts at 1, 2 at 2, etc... then group 1 moves to 2, 2 to 3, etc...

### Homework

- Calculate and submit inventory metrics (e.g., stem density, DBH, basal area) (e.g., Google Sheet)
**see readme file in folder 04**

----------------------------

## 31.10.2024

folder: 03_gnss

## Lecture Block (Thomas P.):

- Position determination
- Introduction to satellite-based positioning
- Why is positioning important for inventories?
- GPS, GLONASS, BEIDOU, GALILEO +
- GNSS uncertainties and influencing factors
- Hemisphere, North, South, On which side of the sky to measure trees?
- Distance/shading from trees
- Minimizing GNSS uncertainties
- RTK, SAPOS, Rover, Base station, Postprocessing

## Exercise Block (Max): Field Exercise!

- **Field exercise** on GNSS
- Groups of 2 people
    - One person tracks, one measures points (circuit around Schlossberg)
- Introduction to EmlidReach, Base, Rover (before the exercise)

What you need:

- **Weatherproof clothing**
- Smartphone
- Avenza Maps App (please download!)
- Materials in folder 03_gnss/exercises

**Meeting point behind Kanonenplatz (https://maps.app.goo.gl/1t6J6wnk2cSg4bkt7) punctually at 15:00 (please try to be there slightly earlier so we can start directly).**

Rough schedule:

- Start at 15:00
- Approx. 15-20 minutes introduction to Emlid Reach Base and Rover
- Independently complete the circuit (approx. 1.5h) and track the points and path using Avenza Maps.
- After the exercise, immediately upload the CSV and GPX online and review the results
- Send CSV and GPX to Max by email (as a backup in case the online app does not work)


## October 24, 2024: Lecture Block (Thomas P.):
- Theory and Introduction to Forestry Inventories
- Introduction to the theory of inventories
- Why inventories?
- Terrestrial inventories
- Inventory design
- Inventory methods

## Exercise (Thomas P., Max F.):

- Application of inventory planning
- Planning an inventory in GIS
- Starting situation for inventory for forestry operations or private forests with a specified area
- Which inventory method (angle count sampling, etc.)?
- Determination of the inventory scope (number of samples/plots)
- Positioning of inventory points
- Regular grid
- Random samples
- Stratification? (e.g., by stands/forest types/topography)