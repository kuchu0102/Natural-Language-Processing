# Natural-Language-Processing
Machine and Deep Learning Classification for Sentiment Analysis On Food Reviews

The advent of web has led to increased customer interaction directly with the businesses and will be an important asset for sentiment analysis as future holds. 
This paper presents a novel approach to tackle the sentiment polarity categorization by choosing the correct vectorization techniques to train models. The experiments tried to conjecture that N-gram model can provide additional performance gain. Logistic bigram model has performed exceptionally well reaching accuracy of around 93.7 % and achieved superior performance over the state-of-the-art methods. Besides, proposed approach can be used to multiclass label categorization in sentiment analysis.
The source code has been kept into two files. One for the Machine learning analysis part and other for the deep learning analysis part.

Process :

![image](https://user-images.githubusercontent.com/61591442/153451075-f55823c9-53ef-49f3-be6f-0019e10400c3.png)

Final Result Comparison:
![image](https://user-images.githubusercontent.com/61591442/153451224-56b3b005-5aba-4958-8147-1334f8939724.png)

Process to view the Results :
The executable has not been generated but the code results can be obtained by running the codes of the two files by steps provided below.

Run steps:
1. After Unzipping the folder, there will be two main code files 'Machine Learning Models.ipynb' and 'Deep Learning CNN Model.ipynb'.
2. Open the files using .ipynb supported softwares like "juypter notebook" or online paltform 'https://colab.research.google.com/'.
3. Download dataset from https://www.kaggle.com/snap/amazon-fine-food-reviews.
4. a). When working with juypter notbook or any other desktop applications extract the downlaoded dataset files in the same folder as .ipynb files and do confirm whether the folder has now file 'Reviews.csv'.
   b). When working with google colab, the 'Reviews.csv' file needs to be uploaded in the drive and provide the correct path in the second line of the code.
5. After the setup has been done run all the cells.
6. Results can be then viewed just below the cells.

Note:

1. The file 'Machine Learning Models.ipynb' can take around 4-6 hours to run completely.
2. The file 'Deep Learning CNN Model.ipynb' can take more than 15 hours to run completely. The time can be reduced by twitchng and decreasing the number of epochs in the below code.
history1=model.fit(
                 x_train, 
                 y_train, 
                 validation_data=(x_val, y_val),
                 epochs=10, 
                 batch_size=64,
                 callbacks=[checkpoint2],
                 shuffle=True)
