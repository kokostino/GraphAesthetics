# GraphAesthetics
---
Goal: Predict links between images which share the same aesthetic <br />
 <br /> <img src="https://github.com/kokostino/GraphAesthetics/blob/main/bsp.png" width="600" /><br /><br />
Method: Link prediction between nodes containing colour, feature, and CV information of images. Node preprocessing and ML-based labelling support [can be found here](https://github.com/kokostino/GraphAesthetics-PreProcessing).

Currently under development on toy data, notebooks so far:

- Node2vec + LightGBM (nx + sklearn)
- GAE (pytorch geometric)
- GraphSAGE (stellargraph + tensorflow)
- GraphSAGE, GCN, GIN (pytorch geometric)
