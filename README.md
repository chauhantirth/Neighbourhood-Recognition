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

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```