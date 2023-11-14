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
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          8.417329788209855,
          52.12840304451484
        ],
        "type": "Point"
      }
    },
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              8.413082159938853,
              52.1285545385044
            ],
            [
              8.415509486060756,
              52.12580322781949
            ],
            [
              8.4225451462367,
              52.12975276310823
            ],
            [
              8.420354171204934,
              52.13155604221143
            ],
            [
              8.413082159938853,
              52.1285545385044
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```