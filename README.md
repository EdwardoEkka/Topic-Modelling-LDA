# YouTube Data Analysis with LDA Topic Modeling

This script enables you to conduct topic modeling on YouTube video titles and examine trends in likes over time for each identified topic. Follow the steps below to analyze your YouTube data:

## Step 1: Requirements

Ensure you have the following installed:

- Python 3.x
- Required Python packages:
  - pandas
  - nltk
  - scikit-learn
  - matplotlib

You can install these packages via pip:

```
pip install pandas nltk scikit-learn matplotlib
```

## Step 2: Prepare Your Data

Format your YouTube data into a JSON file with the structure outlined below:

```json
[
    {
        "videoId": "Your video ID 1",
        "title": "Your video title 1",
        "publishedAt": "YYYY-MM-DDTHH:MM:SSZ",
        "likes": 100,
        "views": 1000
    },
    {
        "videoId": "Your video ID 2",
        "title": "Your video title 2",
        "publishedAt": "YYYY-MM-DDTHH:MM:SSZ",
        "likes": 200,
        "views": 2000
    },
    ...
]
```

Save this file as `data_youtube.json`.

## Step 3: Customize Stop Words (Optional)

If you wish to customize the stop words used for tokenization, you can edit the `stop_words` list in the script. Add or remove words based on your requirements.

```python
stop_words = [
    'for', 'couldn', 'hers', 'so', 'myself', 'themselves', 'each',
    ...
]
```

## Step 4: Run the Script

Execute the script `youtube_analysis.py` using the following command:

```
python youtube_analysis.py
```

## Step 5: Analyze Results

Upon running the script, you'll obtain the following outputs:

- Topic modeling results printed in the console.
- Trend analysis plots for each topic displayed in separate windows.
- A JSON file named `youtube_model.json` containing the topics and titles in each topic.

## Step 6: Customize Analysis Parameters (Optional)

To further customize the analysis, you can modify the following parameters in the script:

- **Number of Topics**: Adjust the `num_topics` variable to alter the number of topics identified by the LDA model.

```python
num_topics = 5
```

## Step 7: Run the Script

Once you've made the necessary adjustments, run the script using the command line or any Python environment:

```bash
python youtube_analysis.py
```

## Step 8: Analyze Results

Following script execution, you'll receive the subsequent outputs:

- Topic modeling results printed in the console.
- Trend analysis plots for each topic displayed in separate windows.
- A JSON file named `youtube_model.json` containing the topics and titles in each topic.

Feel free to delve into the results and perform further analysis!

---

Feel free to enrich the instructions or tailor them to your preferences and the specifics of your script.
