# 🤖 Machine Learning

## 📓 General notes

Dataset used for this exercise is available on this [link](https://opendata.paris.fr/explore/dataset/comptage-velo-donnees-compteurs/export/?disjunctive.id_compteur&disjunctive.nom_compteur&disjunctive.id&disjunctive.name)

The final goal of this project is to initialize a prediction model for hourly bike flow at different points of the city

This project at this point is only the first step on how we need to clean the dataset to begin crossing with different datasets (like weather...) into the goal to make the prediction model

As soon as we understand what we are doing we will update this documentation to help you build your own as we did 🚀

Please reffer to `develop` branch ❤️

## 💾 Data Sample

```json
{
    "datasetid": "comptage-velo-donnees-compteurs",
    "fields": {
        "coordinates": [
            48.83511,
            2.33338
        ],
        "counter": "X2H20012081",
        "date": "2020-10-01T04:00:00+02:00",
        "id": "100003096",
        "id_compteur": "100003096-353242251",
        "installation_date": "2012-02-22",
        "name": "97 avenue Denfert Rochereau",
        "nom_compteur": "97 avenue Denfert Rochereau SO-NE",
        "sum_counts": 0.0,
        "url_photos_n1": "https://www.eco-visio.net/Photos/100003096/https:"
    },
    "geometry": {
        "coordinates": [
            2.33338,
            48.83511
        ],
        "type": "Point"
    },
    "record_timestamp": "2021-11-23T08:00:03.265+01:00",
    "recordid": "ef5a8926e5ffa2afe942a22bce813d3b7b5ed91b"
}
```

## 🥅  Roadmap

Need to handle the cleaning of the data. We could first check all the same elements, check if all the data is without duplicates...