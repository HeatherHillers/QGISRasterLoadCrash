# QGISRasterLoadCrash
I have a set of tifs that cause an AppCrash on load to 2.14.6 and 2.16, either immediately on load or shortly after.  I can load and work with these files without problem in QGIS 2.8.6  

I have produced 4 small hillshade tifs, each less than 1000 Kb in size. Each has a world file and a kml in the same directory.  I have uploaded them to https://github.com/HeatherHillers/QGISRasterLoadCrash

We have a networked Windows 7 32bit environment running OSGeo4W (qgis-ltr) as well as a local Windows 7 32 bit environment running OSGeo4W (qgis-ltr and qgis)  and the problem shows in all 3 installations.  The QGIS 2.8 that loads the files successfully is also running on a networked Windows 32bit environment.  Storing the files on a networked vs. local drive doesn’t seem to impact the problem.

The CRS of the files is 32619.  I have tried eliminating Reprojection in my settings and in the project settings.

I have produced the data by following the instructions in the following 3 (excellent!) tutorials from LASTools, using their test data.  I didn’t get any errors in generation, and the tiles look very nice in 2.8, so I don’t .think. they are corrupt.

http://rapidlasso.com/2013/04/20/tutorial-quality-checking/
http://rapidlasso.com/2013/10/13/tutorial-lidar-preparation/
http://rapidlasso.com/2013/10/20/tutorial-derivative-production/



