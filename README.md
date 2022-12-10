# Lab2_ML_SEC

Steps

- Filepath defined as cl/valid.h5, cl/test.h5 and bd/bd_test.h5 so cl and bd files uploaded to colab under files to access the data in this way.
- bd_net.h5 and bd_weights.h5 also directly uploaded to colab under files and the filepath accesses it directly.
- Remaining code blocks generate B prime and save as zips and also reference its filepath when loading model weights for threshold 2,4,10.
- Clean accuracy and attack success calculated
- Steps repeated for 4, 10 thresholds also
- In the end there is a code block to track clean and attack success rate along with a graph
