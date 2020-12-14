# nlp-project
Natural Language Processing Group Project / Fall 2020

Note on our final model notebook:
Since each of the three subreddits had their own model, we trained identital models for all three (to minimize the effect of the model on the analysis between subreddits.) Due to this, the final-model.ipynb only shows the model for one subreddit, but all three models in `saved_models/` were made from the same architecture.

`master` branch: Do not push directly to master, this is the final product. Merge `develop` into `master`.

`develop` branch: Code changes should begin on branches branching from here, then merge back into `develop`.

`exploration` branch: This branch has "throwaway" code exploration that is peripheral to the `develop` branch.
