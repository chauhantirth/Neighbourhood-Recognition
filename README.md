# Neighbourhood-Recognition
A simple Machine Learning Project based on K Means Clustering Algorithm to recognize neighbourhood across the provided co-ordinates of a location as dataset. 

## Dataset

- Dataset consist of co-ordinates of the places on the maps along with other details, the two main features 'Latitude' and 'Longitude' are required for mapping.
- The dataset I have used is extracted from [OpenStreetMaps](https://www.openstreetmap.org/).

## Workflow

- Step 1: Loading the dataset and filtering it
- Step 2: Using Elbow method to determine the optimal number of clusters
![App Screenshot](https://imgsaver.com/images/2023/11/08/image.png)
- Step 3: Model Training
- Step 4: Plotting the result
![App Screenshot](https://imgsaver.com/images/2023/11/08/image12c2a7226b967bee.png)
- Actual Location:
```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "Bardüttingdorf"},
          "coordinates": [52.128163, 8.412003]
        },
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```