### Test data from actual summaries

The jsonl will contain summaries from BU, PG, and S2S paired with the article. Specifically:

id. The id will be `model-articlenb-sentnb` where model is one of `pg`, `bu`, `s2s`. The sentences are found using spacy_lg model.
claim. The claim will be the corresponding sentence.
text. The article is the main article (lowercase).
label. Label will be empty since we don't have supervision on this.
relevance. Relevance score from human eval.
factuality. Factuality score from human eval.


The file non_shuffled_output.tsv has four columns:

| Article | PG | Baseline | BU |
|----|----|----|----|
