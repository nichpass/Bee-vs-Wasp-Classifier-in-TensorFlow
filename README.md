# Bee vs Wasp Classifier

This jupyter lab shows the preprocessing, training, and testing for a neural network that classifies an image as containing a bee, wasp, or other creature. To re-train this model, you must have this dataset: https://www.kaggle.com/jerzydziewierz/bee-vs-wasp stored in a folder at the same directory level as the notebook.

### Results
Since I was limited to a ~ not so powerful ~ school GPU I had to limit model size (I think it's only around 3 million parameters) though in terms of results it got around 79% validation accuracy. I probably could have gotten better results just doing some transfer learning from ResNet-18 but for the sake of this project I made it from scratch. Hope you enjoy!