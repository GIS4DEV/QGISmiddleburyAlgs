# QGISmiddleburyAlgs
Algorithms for teaching QGIS

These were developed quickly in the QGIS graphic modeler. Future plans are to program them in python and potentially package them as a plugin. 

The DirectionDistance algorithm calculates direction (in degrees) and distance (in the CRS linear units) from a point feature to features in the input layer, and appends these as attributes to the input layer.

The GroupByDissolve algorithm uses SQL to group and dissolve features. It's benefits over other QGIS dissovle algorithms are:
  1. Applies SpatiaLite makevalid() function to repair geometries
  2. Can group by more than one attribute
  3. Can calculate multiple aggregate functions for multiple numeric attributes
