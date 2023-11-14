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
          8.416920705356205,
          52.12816489590932
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
            8.42130722696757,
            52.13058196748335
          ],
          [
            8.41226875351444,
            52.128958737872495
          ],
          [
            8.414989247271222,
            52.12560632536011
          ],
          [
            8.423018224158682,
            52.128514375529164
          ],
          [
            8.421335613967557,
            52.1305914380286
          ]
        ],
        "type": "LineString"
      }
    }
  ]
}
```