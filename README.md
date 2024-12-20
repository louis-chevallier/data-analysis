# Data visualization

## Data-analysis
Given a dataset, discover relationships between variables automatically.

original features : F

## Approach

- set up an auto encoder model : d(e(x)) , appy it to the dataset
- decrease bottlenect width and evaluate the reconstruction error
- identify minimal width
- the inner representation gives a new set of features I





Ik = e(Fi, Fj , ...)

ideally try to enforce e() to be sparse, ie use as few input variable as possible

sort the Fi by decreasing order of significance


Goal : come out with Fi = g(Fj..k)
