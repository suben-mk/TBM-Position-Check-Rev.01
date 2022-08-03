# TBM-Position-Check
**TBM Position** was calculated from local TBM coordinate system (Y, X, Z) and global coordinate system (Easting, Northing, Elevation).
By transformation to TBM center which was 3 reference points (Easting, Northing, Elevation), Target unit, Shield articulation and Shield edge.
Then chainage, deviation of horizontal and vertical were calculated by reference points, accordance to tunnel axis.

**TBM Position Check Result**

PointID | Actual E | Actual N | Actual Elev | Y | X | Z | Transformed E | Transformed N | Transformed Elev | dE | dN | dElev
---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |  ---- |
1 |273006.111 |2107224.288 |-13.351 |-2.572 |-5.902 |0.719 |272999.747 |2107225.262 |-14.069 |-0.003 |0.008 |-0.010|
2 |273005.349 |2107224.184 |-13.025 |-2.464 |-5.141 |1.039 |272999.748 |2107225.250 |-14.062 |-0.001 |-0.004 |-0.004|
3 | | | |-1.990 |-6.114 |1.849 | | | | | | |
4 | | | |-1.447 |-6.118 |2.441 | | | | | | |
5 |273005.549 |2107226.331 |-11.423 |-0.441 |-5.882 |2.639 |272999.749 |2107225.254 |-14.064 |0.000 |-0.001 |-0.005|
6 |273004.661 |2107226.332 |-11.394 |-0.209 |-5.023 |2.668 |272999.751 |2107225.251 |-14.064 |0.002 |-0.003 |-0.005|
7 |273005.319 |2107227.128 |-11.412 |0.390 |-5.863 |2.648 |272999.752 |2107225.245 |-14.062 |0.003 |-0.009 |-0.003|
8 |273004.502 |2107227.359 |-11.514 |0.823 |-5.133 |2.546 |272999.752 |2107225.245 |-14.061 |0.003 |-0.010 |-0.003|
9 | | | |1.037 |-5.520 |1.525 | | | | | | |
10 |273005.059 |2107228.200 |-11.955 |1.483 |-5.887 |2.110 |272999.749 |2107225.255 |-14.065 |0.000 |0.001 |-0.007|
11 | | | |1.351 |-6.053 |1.621 | | | | | | |
12 | | | |1.898 |-5.844 |1.409 | | | | | | |
13 | | | |2.565 |-5.888 |0.751 | | | | | | |
14 | | | |3.137 |-6.117 |0.455 | | | | | | |
15 | | | | | | | | | | | | |
16 |273004.806 |2107228.746 |-15.722 |2.078 |-5.781 |-1.675 |272999.751 |2107225.254 |-14.052 |0.001 |-0.001 |0.007|
17 |273005.146 |2107228.135 |-16.130 |1.401 |-5.953 |-2.081 |272999.751 |2107225.253 |-14.054 |0.002 |-0.002 |0.005|
18 |273005.281 |2107228.002 |-15.932 |1.239 |-6.050 |-1.883 |272999.751 |2107225.252 |-14.053 |0.002 |-0.003 |0.006|
19 |273005.452 |2107227.610 |-16.275 |0.816 |-6.115 |-2.226 |272999.751 |2107225.251 |-14.053 |0.002 |-0.003 |0.006|
20 |273005.253 |2107227.392 |-16.524 |0.653 |-5.866 |-2.475 |272999.751 |2107225.255 |-14.052 |0.001 |0.000 |0.006|
21 |273004.869 |2107227.289 |-16.097 |0.653 |-5.467 |-2.048 |272999.752 |2107225.254 |-14.052 |0.003 |0.000 |0.007|
22 |273005.868 |2107226.017 |-16.617 |-0.832 |-6.112 |-2.554 |272999.746 |2107225.259 |-14.067 |-0.004 |0.005 |-0.008|
23 | | | |-0.916 |-6.052 |-1.801 | | | | | | |
24 |273005.941 |2107225.639 |-16.091 |-1.217 |-6.083 |-2.037 |272999.749 |2107225.259 |-14.058 |-0.001 |0.005 |0.001|
25 |273005.724 |2107225.397 |-16.025 |-1.394 |-5.812 |-1.972 |272999.748 |2107225.258 |-14.058 |-0.001 |0.004 |0.001|
26 | | | |-1.396 |-5.640 |-1.381 | | | | | | |
27 |273005.867 |2107224.990 |-15.983 |-1.835 |-5.852 |-1.937 |272999.740 |2107225.267 |-14.051 |-0.010 |0.013 |0.007|

_Calculated to Center Sheild_


Reference Position |Target unit |Shield articulation |Shield edge
---- |----:|----:|----:|
Chainage |18680.320 |18678.068 |18674.498|
Hor.deviation |-0.018 |-0.019 |-0.021|
Ver.deviation |0.036 |0.024 |0.005|
Easting |273005.377 |273003.200 |272999.749|
Northing |2107226.746 |2107226.169 |2107225.254|
Elevation |-14.056 |-14.057 |-14.059|

_Calculated to TBM Position_
