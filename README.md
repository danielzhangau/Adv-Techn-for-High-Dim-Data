# Advanced Techniques for High Dimensional Data
UQ INFS

Spatial & multimedia databases: multidimensional data management concepts, theories and technologies, focusing on data access methods and similarity query processing for spatial, multimedia and Web-based databases, with particular emphasis on video

## Topics Covered:
1. **Spatial data types and spatial databases**
   - RDBMS data types: numbers, strings and dates
   - SDBMS data types: points, lines and polygons
     - Usages are very similar compared with relational data types
     - Indexing and processing are quite different
   - Spataial data types can help us to understand how other data types should be managed and processed
     - Such as multimedia data
     - Feature extraction and embedding can transform many type of data into vector data
   - Spatial Data Relations
     - Topological, Direction, Metric
    <p float="left">
      <img src="https://user-images.githubusercontent.com/41173132/121759279-3ddf1700-cb68-11eb-9358-80e3f2424ab0.png"/>
      <img src="https://user-images.githubusercontent.com/41173132/121759286-47687f00-cb68-11eb-9667-dd349aab945f.png"/> 
    </p>
   - Spatial Data Operations
     - Basic Spatial Operations
       - Selection, Projection, Amalgamation
       - Containment, Region, Intersection, Overlay, Fusion, Windowing, Clipping, Centre, Boundary
       - Area, Perimeter, Distance
     - Other Spatial Operations
       - Nearest Neighbours, Similarity Search, Skyline Queries
     - Complex Spatial Queries
       - Multiple predictions/operations, spatial sub-queries
2. **Spatial indexing mechanisms**
   - Purpose:
     - Efficiency in processing spatial selection, join and other spatial operations
   - Two strategies to organize space and objects
     - Map spatial objects into 1D space and use a standard index structure (B-tree)
     - Dedicated external data structures (R-tree & Quad-tree)
   - Basic ideas
     - Approximation
       - Bounding box, Grids
     - Hierachical Data Organization
3. **Spatial alogrithm and query processing**
   - KNN Query Processing
   - Skyline Query Processing
4. **Spatiotemporal data management**
   - Definitions: moving objects and trajectories
   - Spatiotemporal queries
     - Spatiotemporal point and window queries
     - Trajectory similarity queries - and similarity measures
       - Lock-step Windows, LCSS, EDR, DTW, ...
   - Spatiotemporal indexing methods
     - Simple ways of indexing spatiotemporal and issues
       - 3D R-Tree
       - HR-Tree
       - TPR-Tree
5. **High-dimensional indexing and search**
   - Dimensionality Curse
     - Many interesting observations
       - Number of partitions, Central hollow/ High overlapping, Nearest Neighbor is not clear...
     - The performance degrades rapidly as dimensionality increases, and eventually underperforms linear scan
     - However, linear scan needs to search the whole data file - affected volumn is 100%
    - Example Indexes: Why do they still exist?
      - R-tree -> X-tree
      - Z-order -> Pyramid
      - Grid -> VA-file
      - Cluster -> iDistance
6. **Multimedia databases**
   - Data representations
     - Image: basic format, abstraction and features (colour, texture and shape)
     - Video: structure
     ![image](https://user-images.githubusercontent.com/41173132/121758953-eab89480-cb66-11eb-9ccb-27521968508a.png)
   - Text-based vs Content-based search
   - Similarity measures
     - P-norm, ViTri, mean distance and DTW
     - Query results evaluation: Precision and Recall
     ![image](https://user-images.githubusercontent.com/41173132/121759006-16d41580-cb67-11eb-9dd4-d1d6919438e8.png)
7. **Route Planning in Road Network**
   - Index Free
     - Dijkstra's, Bi-Dijkstra's, A*, Bi-A*, Landmark
     ![image](https://user-images.githubusercontent.com/41173132/121759070-5864c080-cb67-11eb-8a35-91e928889202.png)
   - Index based
     - Contraction Hierarchy, 2 Hop Labeling  
     ![image](https://user-images.githubusercontent.com/41173132/121759087-687ca000-cb67-11eb-809c-64c50e5d0256.png)

# What I learned: 
- Identify the applications and features of complex data types, including spatial and multimedia data.
- Acquire both principles and hand-on experiences of implementing existing advanced spatial and multimedia processing techniques and databases.
- Examine the major issues of spatial and multimedia data management systems.
- Analyze and evaluate existing research methods, creative to identify and define problems, and innovative for their solutions for multimedia database management.

