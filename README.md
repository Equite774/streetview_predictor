# streetview_predictor
A deep learning model to regress coordinates onto Google Streetview images.

Dataset pulled from https://www.kaggle.com/datasets/ayuseless/streetview-image-dataset.

The model really isn't particularly good because 25k images is not nearly enough for this task.

Architecture-wise, current design is a multi-layer CNN with dropout followed by several dense layers. (Perhaps I should decrease complexity)
