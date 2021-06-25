# Learning of DVC

There are so far 3 versions of data: <br>
* v0.0.1 - Just raw data about Hogwarts graduates
* v0.1.0 - Added a new column 'average grade'
* v0.1.1 - Added some new rows

## To switch between data
```
git checkout v0.0.1 data/data.csv.dvc
```
```
dvc checkout
```

## To get back
```
git checkout main
```
```
dvc checkout
```
