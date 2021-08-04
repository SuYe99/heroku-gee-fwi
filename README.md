# heroku-gee-fwi
Heroku App for Google Earth Engine FWI

## Local Development

Environment installation

```
$ conda create -n dashboard python=3.9
$ conda activate dashboard
$ conda install -c conda-forge geemap jupyter-flex voila
```

Run the voila server locally

```
$ voila --template=flex FireDangerRatingSystem.ipynb
```