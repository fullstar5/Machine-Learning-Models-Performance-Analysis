CSV files are read in program without first column, 'review-text-cleaned' column will be converted into sum of ASCII value and apply normalization process.

Differnt trainning, validation and test sets are passed into techniques (describe below) to observer outputs.

Zero-R and Random baseline were implemented to compare with other methods.

MNB and GNB were implemented as first supervised learning technique, 'alpha' value is adjusted multiple times to get maximum performance.

LR is implemented as second supervised learning technique, 'max_iter', 'weight' and 'penalty' value is adjusted multiple times to get maximum performance.

KNN is implemented as third supervised learning technique, 'n_neighbors' value is adjusted multiple times to get maximum performance.

MLP is implemented as fourth supervised learning technique, 'hidden_layer_sizes' and 'learning_rate' value is adjusted multiple times to get maximum performance.

Dataset will be splitted, group by gender. And passed into each methods again to observe output differences. Gender and positive-negative value will be calculated, graph will be drawn.

Kaggle competition file will be generated.