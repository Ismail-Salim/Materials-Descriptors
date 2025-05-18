# Materials-Descriptors

This is a repository for the choice of descriptors (1D Descriptors) for materials in data-driven modeling of chemical reactions.

## ** 00_Mendeleev_Elements_Properties.ipynb 
* As an example, for chemical elements, the Periodic Table-Based Descriptors (Elements Properties) can be extracted and used as descriptors.

### The first part is to extract these properties using the "Mendeleev" Library according to the elements in the data point.
* data files: 
-Added_Elements_Properties.xlsx
-Mendeleev_units_updated.xlsx
### The second part of the code is to extract the "mat2vec embeddings" from "https://github.com/materialsintelligence/mat2vec"
* data files: 
-promoter_mat2vec_embeddings.csv
### The third part of the code is to add both representations to the dataset (properties and embeddings)

