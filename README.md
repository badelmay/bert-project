Scoring Model with BERT in Amazon Reviews
This project aims to score comments using the BERT model on Amazon product reviews. The project trains and evaluates the model using the “Amazon US Customer Reviews Dataset” from Kaggle.

About the project
In this project, the BERT (Bidirectional Encoder Representations from Transformers) model was used to score comments on Amazon product reviews. The project aims to estimate points for comments by analyzing their texts.

Used technologies
Python Transformers (Huggingface) PyTorch pandas NumPy scikit-learn

Data set
"Amazon US Customer Reviews Dataset" taken from Kaggle is used in the project. This data set consists of rows, each containing a review text (review_body) and a label. Tags represent the rating score of the review.

Model Training
The BERT model was trained with fine-tuning using Huggingface's transformers library. During the training process, the model was evaluated with metrics such as accuracy, precision and recall rate.

Model Testing
The trained model was tested on local data and its performance was evaluated. During the testing process, the results were analyzed along with the model's accuracy and other metrics.

Results
The trained model can effectively analyze Amazon product reviews and give accurate scores to the comments. The performance of the model was evaluated with metrics such as accuracy, precision and recall rate.
