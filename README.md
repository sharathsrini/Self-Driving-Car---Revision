# Self-Driving-Car---Revision

### Particle Filter Localization:
* How do we resample in particle filter?
* How does sensor fusion come in  place for localization.?
* Is resampling probabilistic or determistic 

### GNSS Localization:
How does a GPS work
* GPS
* GPS + RTK
* GPS + IMU

1. How do you calculate or translate the timestamp fronm the satellite in order to obtain time stamped sensor readings?
2. Triangulation theory of mapping using GPS
3. GPS accuracy < single digit number.
4. RTK and its Principle.
5. Limitations of RTK.

### Lidar Based Localization:
1. Sparse
  * Landmarks
2. Dense
  * ICP
  * NDT
  
#### Sparse:
 * Create landmarks by clustering the point cloud. 
 * What would we want identify and classify surroundings as stationary and objects that are in  motion? 
 * False positives and false negatives in clustering.
 
 #### Dense:
 * Probabilistic approach without clustering and landmark generation.
 * Match point to point
 * ICP involves rotation and translation olf the points that match with the reference point, which would have a function..
 * NDT <----- Normalized distributed translation.
 * A boxhole
