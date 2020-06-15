# DSL 2020

# Semi-Supervised Topic Discovery and Sentiment Extraction on Textual Feedback Systems

Aditya Gadepalli (19BM6JP08) | Srijan Gupta (19BM6JP19) | Anudeep Immidisetty (19BM6JP54)


Consumer facing organizations need to constantly keep track of feedback/grievances from their stakeholders. Relevant feedback must be classified and incumbent issues need to be clustered into appropriate categories. This clustering needs to be assessed over several indicators and benchmarks that convey effect over improvements in functional and operational utility.  We propose a semi-supervised approach for performing relevant news article selection using extensive text cleaning, pre-trained RoBERTa embedding and Latent Semantic Analysis, followed by extensive exploratory data analysis, complex network analysis and sentiment extraction on the developed corpus. The processed articles are subjected to Latent Dirichlet Allocation, Hierarchical Dirichlet Process and Clustering to discover potential topics in an unsupervised manner. We then label the articles accordingly to devise a training set for building a multi-class classifier for topic categorization and assignment. The Top-3 accuracy metric is chosen along with several other indicators to understand the performance of the classifier and also ascertain the severity and other aspects of the incoming news articles. New topic discovery is also performed to improve the classifier classes and the model is  re-calibrated at appropriate intervals to stay above human benchmark in scale and accuracy.

## Project Organization - File Structure
    ├── README.md                        <- Project Homepage
    |── Report                           <- The Report PDF of the paper in standard format
    |── Slides                           <- The PPT and PDF of the final presentation
    |── csv_files                        <- The csv files used within the ipynb
    ├── images                           <- The image files used within the ipynb
    ├── ipynb_files                      <- The ipython notebook of the complete implementation
    ├── tableau_files                    <- Contains the tableau workbook file of the Dashboard

![Screenshot](flowchart.png)
