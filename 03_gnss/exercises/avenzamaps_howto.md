# Guide: Using Avenza Maps for Path Tracking and Point Measurement and Processing in QGIS

## 1. Installation and Setup of Avenza Maps

- Download the app: Download and install the Avenza Maps app from the App Store (iOS) or Google Play Store (Android).
- Registration: Optionally, you can create an account with Avenza to synchronize your data. This is **not** necessary for our purposes.

## Workflow:

You have a choice between two workflows...

- Either you navigate to the points using Google Maps and simply load the GPX with the stations there
- Or you can also use Avenza Maps for this; then you have everything in one app, **but you must later pay attention to "active layers"!**

## 2. Importing a Layer into Avenza Maps

- Open Avenza Maps and navigate to "Layers" at the bottom.
- Tap the ‘+’ icon at the top right and select "Import Layers."
- Choose the file (in our case, "03_gnss.gpx"), and it will be imported into Avenza Maps.
- The layer should now be displayed on your base map.

You should now see the individual stations and can navigate to them. **Now you must ensure that you create a new layer for your measurements and declare it as the "active layer":**

- Set as active layer:
    - Now go to "Open Base Map"
    - Click on the layer icon at the bottom right
    - Then select "Set as active layer" with the three dots next to the layer "name-of-your-own-layer"

Now, when you add points, you should be able to add them to your own layer. At the end of the exercise, you can easily export your points.

## 3. Path Tracking with Avenza Maps

**Start Tracking:**

- Ensure that your GPS is activated.
- **Make sure that your newly created layer is the active layer!!**
- Tap the measurement icon at the bottom left and select "Measure GPS Tracks."
- You can then start a track. Keep it active until the exercise is complete :)
- The app will now begin to track your location and record the path on the map.
- Be sure to stay on the designated path (e.g., always on the right side of the path).
- The recorded path will be displayed as a line on the map.

**End Tracking:**

Once you have finished the circular route, tap the track icon again and select "Stop Tracking."  
The path will now be saved as a completed element.

## 4. Measuring Points

**Insert Point:**

- **Make sure that your newly created layer is the active layer!!**
- Tap the pin icon at the bottom right during the circular route to save a new point on the map.
- Your current position will be automatically marked as a point.
- Naming Points:
    - After inserting the point, you can name it, e.g., A, B, etc.
    - Add a description (Coverage): Enter a number between 1 and 10 (nothing else!) that approximately reflects the coverage above you. For example, if you are in a forest with many trees, 8 or 9 would be a realistic value. In open air, it would probably be a 1 or 2.
    - Save the point and then proceed to the next one!

## 5. Exporting the Data

**Exporting the Path:**

- Open the list of saved tracks (under ‘My Maps’ > Track icon).
- Select the tracked path and tap the three dots (⋮) next to the track name.
- Choose ‘Export’ and export the path as KML (KML is sufficient for importing into QGIS).

**Exporting the Points:**

- Open the list of saved points (under ‘My Maps’ > Point icon).
- Select all points you saved during the exercise (NOT the ones we provided you!).
- Export the points as CSV so that you can find them again and load them into QGIS on your home PC.

## Now continue following the instructions in ex03.pdf
