![Logo](./Images/Logo.png)


### Step 0: Step by Step Guide to begin working with your data

[Download the workshop PDF](https://github.com/Human-Centered-Engineering-Lab/EXPERIMENTING-WITH-LARGE-ETHNOGRAPHIC-DATA-workshop/raw/main/Images/StepbyStep%20Prep_Workshop%2002-10_HCELab.pdf)

---

### Step 1: Generating Sentence Embeddings with Sentence Transformers

This script uses the SentenceTransformers library to generate sentence embeddings from any type of text. Here, we apply it to interview transcripts, enabling us to analyze how interviews relate based on their content. The text is transformed into numerical embeddings that capture semantic meaning, making them ideal for tasks like similarity detection or data clustering.

[Learn more about Sentence Transformers](https://sbert.net/docs/sentence_transformer/pretrained_models.html)

---

### Step 2: Visualizing Sentence Embeddings with DataMapPlot

Once the sentence embeddings are generated, the next step is to visualize them. This script utilizes DataMapPlot to create an interactive plot, showing how the embeddings are clustered and organized in a 2D space.

The visualization helps in understanding the structure of the data and identifying patterns or clusters of sentences that share semantic similarities.

[Learn more about DataMapPlot](https://datamapplot.readthedocs.io/en/latest/)

---

### Visualization 1: DataMapPlot without Labels

![DataMapPlot without Labels](./Images/Nolabels.png)

This first visualization is created without any labels. It shows how different clusters are formed based on the semantic similarity between interviews. The goal here is to explore the clusters and start identifying patterns in the data, without the influence of labels. Once we have a clear view of these clusters, we can move on to annotating them for further analysis.

