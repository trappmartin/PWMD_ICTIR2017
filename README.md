# Position-Sensitive Word Mover’s Distance

Code accompanying the paper **Retrieving Compositional Documents Using Position-Sensitive Word Mover’s Distance**.

Twin Films Dataset
-------
The twin dataset described in the publication is found under:

```text
dataset
```
where the extracted IMDB mapping are found in
```
dataset/imdb-mappings.csv
```
the ground truth mappings of twin films described on wikipedia are listed in
```text
dataset/twin-films.csv
```
and the extracted plot keywords are found in binary format (python pickle) under
```text
dataset/plotKeywords.pkl
```
.

Example Code
-------
An example implementation of the **Position-Sensitive Word Mover’s Distance** can be found under:

```text
code/pwmd.py
```

To run the code, please ensure to install the following python packages in advance.

```text
python 3
spacy
pyemd
```

Citation
-------
Please use the following citation:

```text
@inproceedings{Trapp2017b,
    title={Retrieving Compositional Documents Using Position-Sensitive Word Mover’s Distance},
    author={Trapp, Martin and Skowron, Marcin and Schabus, Dietmar},
    booktitle={Proceedings of the ACM International Conference on the Theory of Information Retrieval},
    year={2017},
    doi={10.1145/3121050.3121084}
   }
```

License
-------
The code is licensed under the MIT License.