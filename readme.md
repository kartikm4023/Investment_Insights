# News Sentiment Analysis with Llama 3

**Objective:** Predict the sentiment of a news title.

**Instructions:**

1. **Download the local Llama model:**
   - Visit https://ollama.com/ and download the Llama 3 model.

2. **Run the model locally:**
   - Open your terminal and execute the following command to pull the image and run the model:
     ```bash
     ollama run llama3 
     ```

3. **Run the Jupyter notebook:**
   - Open the provided Jupyter notebook.
   - Experiment with the following classifiers:
     - **Zero-shot classifier:** Use the pre-trained Llama model as is to predict sentiment without any additional training.
     - **Few-shot classifier:** Fine-tune the model by providing a few examples of news titles with their corresponding sentiment labels.

**Next Steps:**

- **Validate the output:**
   - Test the model on news titles from different tickers/companies and assess the accuracy of the predictions.
- **Expand few-shot training:**
   - Improve the model's performance by providing more labeled examples for few-shot learning.
- **Analyze full news content:**
   - Extend the project to analyze the sentiment of the entire news article, not just the title.
