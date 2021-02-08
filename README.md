## Debug Log:

1. Not balancing classes with class weights raises accuracy to over 57% ???
2. Validation acc > training acc - Maybe due to heavy drop-out (0.5)?
3. It seems like network starts to overfit without drop-out (training accuracy increases, while validation accuracy is the same)
4. No change with learing rate [1e-2, 1e-7]
5. No change with different optimizer (Adam, SGD)
6. New validation set needs to be created, with Patient ID as a filter for split.
7. 

## TODO:

1. Make classification
