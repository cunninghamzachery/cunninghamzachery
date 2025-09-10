# Testing
```stl
solid cube_10x10x10
  // Face 1: Bottom face (-Z)
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 10.0 10.0 0.0
      vertex 10.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 10.0 0.0
      vertex 10.0 10.0 0.0
    endloop
  endfacet
  // Face 2: Top face (+Z)
  facet normal 0.0 0.0 1.0
    outer loop
      vertex 0.0 0.0 10.0
      vertex 10.0 0.0 10.0
      vertex 10.0 10.0 10.0
    endloop
  endfacet
  facet normal 0.0 0.0 1.0
    outer loop
      vertex 0.0 0.0 10.0
      vertex 10.0 10.0 10.0
      vertex 0.0 10.0 10.0
    endloop
  endfacet
  // Face 3: Back face (-Y)
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 10.0 0.0 0.0
      vertex 10.0 0.0 10.0
    endloop
  endfacet
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 10.0 0.0 10.0
      vertex 0.0 0.0 10.0
    endloop
  endfacet
  // Face 4: Front face (+Y)
  facet normal 0.0 1.0 0.0
    outer loop
      vertex 0.0 10.0 0.0
      vertex 10.0 10.0 10.0
      vertex 10.0 10.0 0.0
    endloop
  endfacet
  facet normal 0.0 1.0 0.0
    outer loop
      vertex 0.0 10.0 0.0
      vertex 0.0 10.0 10.0
      vertex 10.0 10.0 10.0
    endloop
  endfacet
  // Face 5: Left face (-X)
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 10.0
      vertex 0.0 10.0 10.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 10.0 10.0
      vertex 0.0 10.0 0.0
    endloop
  endfacet
  // Face 6: Right face (+X)
  facet normal 1.0 0.0 0.0
    outer loop
      vertex 10.0 0.0 0.0
      vertex 10.0 10.0 0.0
      vertex 10.0 10.0 10.0
    endloop
  endfacet
  facet normal 1.0 0.0 0.0
    outer loop
      vertex 10.0 0.0 0.0
      vertex 10.0 10.0 10.0
      vertex 10.0 0.0 10.0
    endloop
  endfacet
endsolid cube_10x10x10
```
# Testing 2
