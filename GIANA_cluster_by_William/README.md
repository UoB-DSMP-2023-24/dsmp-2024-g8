REF: https://www.nature.com/articles/s41467-021-25006-7
GITHUB: https://github.com/s175573/GIANA5

In the original GIANA4.1.py, we need to resourse package which is only avaliable for Mac and I am using Winsdows, so I comment the 'import resource'.
From the reference github, we do not have the data of TRBV variable gene, so we use the Method 3 'Clustering without TRBV variable gene', in that case, the input data can contain only one column of CDR3s, so I Extract the'cdr3 'column in vdjdb.txt and save it as a txt file as 'cdr3_column.txt'.
The cluster output is storaged in the file named "cdr3_column--RotationEncodingBL62.txt"
