# rook-search

Run docker container with ElasticSearch.

ElasticSearch has an index for fixes that get applied to datasets provided by
the Rook subsetting service.

## Run docker container

```
cd docker/
docker-compose up
```

## Run notebooks to reindex

View notebooks online:
* [NBViewer](https://nbviewer.org/github/cehbrecht/rook-search/blob/main/notebooks/)

Run notebooks locally:
```
cd notebooks
mamba env create
jupyter lab
```
