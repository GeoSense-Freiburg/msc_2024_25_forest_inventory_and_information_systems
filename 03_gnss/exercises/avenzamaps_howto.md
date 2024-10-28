# How-To: Avenza Maps

## 1. Installation and Setup of Avenza Maps

- Download the app: Download and install the Avenza Maps app from the App Store (iOS) or Google Play Store (Android).
- Registration: Optionally, you can create an account with Avenza to sync your data. This is **not** required for our purposes.

## 2. Importing a Layer into Avenza Maps

- Open Avenza Maps and navigate to "Layers" at the bottom.
- Tap the ‘+’ symbol at the top right and select "Import Layers".
- Select the file (in our case "03.kmz"), and it will be imported into Avenza Maps (or via QR code).
- The layer should now be displayed on your base map.

You should now see the individual stations and can navigate to them. **Now you need to make sure to create a new layer for your measurements and declare it as the "active layer"**:

- Set as active layer
    - Open the "Base Map"
    - Tap the layer symbol at the bottom right
    - Then select "Set as active layer" from the three dots next to the layer "name-of-your-own-layer"

Now, when you add points, they will be added to your own layer. At the end of the exercise, you can easily export your points.

## 3. Path Tracking with Avenza Maps

**Start tracking:**

- Make sure your GPS is enabled.
- **Ensure that your newly created layer is the active layer!!**
- Tap the measurement symbol at the bottom left and select "Measure GPS tracks".
- Then you can start a track. Keep it active until the exercise is finished :)
- The app will now start tracking your location and recording the path on the map.
- Make sure to always stay on the designated path (e.g., always on the right side of the path).
- The recorded path will be displayed as a line on the map.

**Stop tracking:**

Once you have completed the loop, tap the track symbol again and select "Stop Tracking".
The path will now be saved as a completed element.

## 4. Measuring Points

**Insert point:**

- **Ensure that your newly created layer is the active layer!!**
- During the loop, tap the pin button at the bottom right to save a new point on the map. **Make sure your position is at your current location!!!**
- Your position will automatically be marked as a point.
- Naming points:
    - After inserting the point, you can name it, e.g., A, B, etc.
    - Add a description (coverage): Write a number between 1 and 10 (nothing else!), which roughly reflects the coverage above you. For example, if you are standing in a forest under many trees, 8 or 9 would be a realistic value. In open sky, probably a 1 or 2.
    - Save the point and then move to the next one!

## 5. Exporting Data

**Export the path:**

- Open the list of saved tracks (under ‘My Maps’ > Track symbol).
- Select the tracked path and tap the three dots (⋮) next to the track name.
- Select ‘Export’ and export the path as GPX (GPX is sufficient for import into QGIS).

**Export the points:**

- Open the list of saved points (under ‘My Maps’ > Point symbol).
- Select all the points you saved during the exercise (NOT the ones we provided!).
- Export the points as CSV so that you can find them again!

## Now follow the instructions in ex03.pdf
