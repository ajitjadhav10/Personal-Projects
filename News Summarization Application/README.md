View Project Presentation: https://docs.google.com/presentation/d/1zjYIYbcskeXCdGEzs24SSesAEPgx_yPd9Re2UkVk6Y0/edit?usp=sharing

Project Summary:



- The News Summarization Application is built on Streamlit using a fine tuned T5 transformer
- The pre-trained T5 transformer has been fine-tuned on CNN/Daily Mail news dataset (https://huggingface.co/datasets/cnn_dailymail).
- This fine-tuned model is then used to build an interative web-application using Streamlit.
- This model has been saved on the Hugging Face hub from where others can directly use it without the need to train it again using the following link: https://huggingface.co/ajitjadhav/t5-small-finetuned-t5-summarization.
- The performance of this model has been evaluated by computing the ROUGE score for the generated summaries.
- We also computed the Flesch Reading Ease test score of the generated summary to ensure that we have generated easy-to-understand summaries for the user.


Features of Streamlit Application:
- Our application allows users to read summaries of the latest news articles. 
- It also allows users to filter news summaries of a category of their choice. 
- It allows users to determine the number of articles to summarize with the help of a slider.
- Our application also has a feature that makes it possible for users to paste news article text as input and generate summaries at the click of a button.


