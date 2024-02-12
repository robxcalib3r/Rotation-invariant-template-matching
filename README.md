# Rotation invariant (Similar) Object/Particle Detection
Detects location and rotation of each (similar) objects/particles (You have to select the shapes first)
As particles move around the images, it creates bounding boxes around them.
The location(x,y) and rotations (from center, $\theta$ and each axis, $\omega$) 

### v0.6
1. Now, per frame data are being exported in CSV 
2. Specific frames can be selected for computation

### v0.5
1. Singularization based on confidence (after match templating)
2. individual colors (fixed for all systems)
3. Individual rotation angles plot
4. individual rotations added into CSV

### v0.4
1. Seperated shapes to create templates
2. Implemented thesholding and contouring
3. Applied matching template on contours
4. trajectory output functionality added
5. CSV output polished
6. x, y coordinates added to output csv

### Shortcomings
1. Sometimes it misses the detection
