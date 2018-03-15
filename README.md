# Goldenrod-Wind-Speed-Data

Wind Speed Data from Goldenrod Field in Clifton Park NY July 2015
-----------------------------------------------------------------
Data was collected in the field in front of Enterprise, at the corner of 21st Century Park Drive and Route 146, in Clifton Park, NY (N 42 degrees 52 minutes 10.29 seconds, W 73 degrees 50 minutes 25.99 seconds).  Data was collected weekly on Wednesday mornings, and visits lasted from 2.5 hours to 4 hours.  Wind data was collected starting roughly 10 cm over the mean height of the tallest plot and moving 5 cm lower with every set of readings until the wind no longer registered on the anemometer.  Three readings were performed at each height.  

When the wind speed was no longer readable, the anemometer was placed in the air above the plot, allowed to catch a breeze, and pulled down until the anemometer stopped moving.  Efforts were made to not block the wind by moving around the plant and/or crouching down before repeating readings.  The anemometer is NIST Traceable certified to have an error of +/-5 % and cannot read wind speeds below 0.1 m/s.  

At each site measurements were taken, the height of the plant to the top of the stem, the height of the plant to the top of the tallest leaf, the number of goldenrod neighbors within a hula hoop of 33 inch diameter, and the number of total neighbors within a hula hoop of 33 inch diameter were recorded as well.  

Data from these measurements is compiled in several documents:

-Original Data for Goldenrod.xlsx contains the full data as recorded in the field.

-Wind Speed Data.csv contains the data used to model wind speed profile in the field as described in Appendix B.3 of my thesis.  From left to right, data in each column are measurements of the height at which wind was observed (cm), plant height to the top of the stem (cm), plant height to top of tallest leaf (cm), mean plant height in patch (cm), number of goldenrod stems per m^2, number of all plants per m^2, wind speed in Albany (mph), wind speed in Schenectady (mph), and the wind speed measured (m/s).  

-roughnesslengthdata..csv contains the Roughness Length Data used to estimate the roughness length of the field in Appendix B.2 of my thesis.  From left to right, data in each column are measurements of plant height to the top of the stem (cm), plant height to top of tallest leaf (cm), mean plant height in patch (cm), number of goldenrod stems per m^2, number of all plants per m^2, wind speed in Albany (mph), wind speed in Schenectady (mph), and the height (cm) at which the wind stopped during that measurement.  


Modeling Leaf Area as Plants Grow
---------------------------------
In addition to collecting data on wind speed through the field and the roughness length of the goldenrod field, several plants were collected from the field on July 28, 2015.  For each plant, height, length, and width of each leaf were measured.  We estimated the leaf area from these measurements using the formula for the area of an ellipse.  In order to estimate leaf area for our goldenrod plants as they grow, we used the data for six plants which had only a single stem.  Many plants were removed from the original data set for having multiple stems, which would make it difficult to compare the two sets of data. From left to right, data in each column are height at which plant was located (cm), length of leaf (cm), width of leaf (cm), and leaf area (cm^2) as estimated using the area of an ellipse with the measured length and width.  Data from plants with a single stalk were used to estimate leaf area in the field and are provided in:

-Plant 1 Leaf Area.csv

-Plant 2 Leaf Area.csv

-Plant 3 Leaf Area.csv

-Plant 4 Leaf Area.csv

-Plant 5 Leaf Area.csv

-Plant 9 Leaf Area.csv
